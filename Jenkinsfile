
pipeline {
    agent any

    stages {
        stage('Welcome') {
            steps {
                echo 'Hello Ammar!'
                echo 'GitHub Webhook to Jenkins Pipeline'
            }
        }

        stage('Check Repository') {
            steps {
                sh 'echo "Repository files:"'
                sh 'ls -la'
                sh 'echo "README content:"'
                sh 'cat README.md'
            }
        }
    }
}
