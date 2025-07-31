pipeline {
    agent any

    stages {
        stage('Hello World') {
            steps {
                echo 'Hello, World! Jenkins Pipeline is Working!'
            }
        }
    }

    post {
        always {
            echo 'Pipeline Execution Finished.'
        }
    }
}
