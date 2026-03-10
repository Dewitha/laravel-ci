pipeline {
    agent any

    stages {

        stage('Check Tools') {
            steps {
                sh 'git --version'
                sh 'php -v'
                sh 'composer -V'
            }
        }

    }
}
