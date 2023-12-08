pipeline {
    agent any
    
    tools {nodejs "node"}
    
    stages {
        stage('install') {
            steps {
                bat 'npm install'
                
            }
        }
         stage('Build') {
            steps {
                bat 'npm run build'
                
            }
        }
    }
}
