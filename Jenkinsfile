pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/username/repo.git'
            }
        }
        stage('Run Ansible Playbook') {
            steps {
                sh 'ansible-playbook -i /var/lib/jenkins/inven /var/lib/jenkins/playbook.yaml'
            }
        }
    }
}
