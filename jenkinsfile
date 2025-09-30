pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo "✅ Checking out code from GitHub..."
                git branch: 'main', url: 'https://github.com/<your-username>/<your-old-repo>.git'
            }
        }

        stage('Build') {
            steps {
                echo "🚀 Build Stage Running..."
                sh 'ls -l'
            }
        }

        stage('Test') {
            steps {
                echo "🧪 Test Stage Running..."
            }
        }

        stage('Deploy') {
            steps {
                echo "📦 Deploy Stage Running..."
            }
        }
    }
}
