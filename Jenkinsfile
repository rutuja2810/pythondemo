pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'python helloworld.py' 
                echo '${params['name']}' 
                
            }
        }
    }
 }
