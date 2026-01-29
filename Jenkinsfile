pipeline {
    agent any 
    stages{
        stage ("build") {
            steps {
                echo 'building the image...'
            }
        }

        stage ("test") {
            steps {
                echo 'testing the image...'
            }
        }

        stage ("deploy") {
            steps {
                echo 'deploying the image...'
            }
        }
    }
        post {
            always {
                echo 'always runs'
            }
            success {
                echo 'pipeline successfull'
            }
            failure {
                echo 'pipeline failed'
            }
        }
}