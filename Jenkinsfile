pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
               ansiblePlaybook installation: 'ansible', inventory: 'hosts', playbook: 'playbooks/deploy_servers.yml'
            }
        }
    }
}
