pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'python helloworld.py' 
                sh '${params['name']}' 
                echo 
            }
        }
    }
 }
