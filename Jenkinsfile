pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post{
        always{
            emailext body: 'pipline demo', subject: 'pipeline', to: 'thusharthimmaiah07@gmail.com'
        }
    }
}
