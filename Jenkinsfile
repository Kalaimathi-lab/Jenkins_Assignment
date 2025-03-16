pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                build job: 'Compile'
            }
        }
        stage('Code Review') {
            steps {
                build job: 'Code Review'
            }
        }
        stage('Unit Test') {
            steps {
                build job: 'Unit Test'
            }
        }
        stage('Package') {
            steps {
                build job: 'Package'
            }
        }
        stage('Deploy') {
            steps {
                build job: 'Deploy'
            }
        }
    }
}
