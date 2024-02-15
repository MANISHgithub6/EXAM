pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'build process'
            }
        }
        stage('test') {
            steps {
                echo 'test process'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploy process'
            }
        }
    }
    post{
        always{
            emailext body: 'pipline demo', subject: 'pipeline', to: 'thusharthimmaiah07@gmail.com'
        }
    }
}

