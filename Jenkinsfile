 pipeline {     
    agent any
    
    tools {
        jdk 'jdk17'
        maven 'maven3'
    } 

    stages {
        
         
        stage('Compile') {
            steps {
            sh  "mvn compile"
            }
        }
        
        stage('tests') {
            steps {
                 sh "echo test success"
            }
        }
        
        stage('Build') {
            steps {
                sh "mvn package"
            }
        }
    }
}
