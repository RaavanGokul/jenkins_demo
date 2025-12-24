pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git credentialsId: 'github-creds',
                    url: 'https://github.com/<your-username>/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Pipeline is running"
            }
        }
    }
}
