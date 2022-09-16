pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'python helloworld.py'
            }
        }
          stage('Paramete') { 
            steps {
                echo 'name'
                echo '${name}'
                sh 'echo 'Hello...'
                sh 'echo '${params['name']}''
                
        }
    }
    }
 }
