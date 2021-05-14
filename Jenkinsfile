pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello Jagdish ,I am in build stage'
                python /home/jagdish/jenkins-pipleline/jenkins-pipleline-example/sample.py
                
            }
        }
        
         stage('Deploy') {
            steps {
                echo 'Hello Jagdish , I am in deploy stage'
            }
        }
        
         stage('Test') {
            steps {
                echo 'Hello Jagdish , I am in Test stage'
            }
        }
        
         stage('Release') {
            steps {
                echo 'Hello Jagdish , I am in Release stage'
            }
        }
    }
}

