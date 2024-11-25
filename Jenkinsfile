pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Clones the Git repository from the specified branch
                git url: 'https://github.com/AbhiRaj4860/Assignment2.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Replace with your actual build command, e.g., Maven, Gradle, etc.
                // sh './build.sh' (uncomment and modify if using a build script)
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Replace with your actual test command, e.g., unit tests, integration tests, etc.
                // sh './test.sh' (uncomment and modify if using a test script)
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // Replace with your deployment command or script
                // sh './deploy.sh' (uncomment and modify if using a deploy script)
            }
        }
    }
}
