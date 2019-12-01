pipeline {
agent any
    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/moshekenan7/gitTest.git'
            }
        }
        stage('build') {
            steps {
                bat 'python 1.py'
            }
        }
    }
}
