pipeline {
    agent any
    
    tools {nodejs "node"}
    
    stages {
        stage('Build') {
            steps {
                bat 'npm install'
                git credentialsId: 'mdits', url: 'https://github.com/lalammagarihussain/react_jenkins.git'
            }
        }
        
    }
}
