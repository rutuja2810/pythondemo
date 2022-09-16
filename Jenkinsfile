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
                sh 'echo 'Hello...'
                sh 'echo '${params['name']}''
        }
    }
    }
 }
