pipeline {
    agent any

    stages {

        stage('Github Repo Trigger') {
            steps {
                echo 'GitHub Webhook Trigger Stage'
            }
        }

        stage('Checking Trigger') {
            steps {
                echo 'Build Triggered'
            }
        }
    }

    post {
        always {
            echo 'Final Stages Process'
        }

        success {
            echo 'Trigger Success'
        }

        failure {
            echo 'Trigger Failed'
        }
    }
}
