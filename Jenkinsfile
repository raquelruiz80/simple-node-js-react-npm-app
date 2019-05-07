pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3000:1111' 
        }
    }
    
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
