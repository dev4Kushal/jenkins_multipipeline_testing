pipeline {
    agent { label 'my-agent-label' }

    stages {
        stage('Checkout') {
            steps {
                // Pull code from the repository
                checkout scm
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands here (e.g., `npm test` or `pytest`)
            }
        }
    }
        
}
