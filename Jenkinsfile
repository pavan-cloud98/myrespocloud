pipeline {
    agent any

    stages {
        stage('Checkout from Git') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/pavan-cloud98/myrespocloud.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building the project..."
                sh "echo build commands go here"
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                sh "echo test commands go here"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying..."
                sh "echo deploy commands go here"
            }
        }
    }
}
