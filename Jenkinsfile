pipeline {
    agent any 

    stages {
        stage('Build Assets') {
            agent any 
            steps {
                echo 'Building Assets...'
               sh 'yum install httpd -y'
            }
        }
        stage('Test') {
            agent any
            steps {
                echo 'Testing stuff...'
            }
        }
        
        
        stage('deploy') {
            agent any
            steps {
                echo 'deploy...'
            }
        }
        
        
    }
}
