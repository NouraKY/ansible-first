pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
               ansiblePlaybook  inventory: 'hosts', playbook: 'playbooks/deploy_servers.yml'
            }
        }
    }
}
