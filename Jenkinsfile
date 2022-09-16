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
                sh "echo ${prams.name}"
                echo 'name'
                echo '${name}'
                sh 'echo 'Hello...'
                sh 'echo '${params['name']}''
                
        }
    }
    }
 }
