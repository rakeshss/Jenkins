pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello World, from branch!!"'
            }
         }   
            
         stage('test deploy') {
            steps {
                sh 'echo "deploying to test"'
            }   
        }
        
        stage('Automation') {
            steps {
                sh 'echo "running automation test cases"'
            }   
        }
    }
}