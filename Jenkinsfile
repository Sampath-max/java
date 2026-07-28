pipeline {
    agent {
    }

    stages {
        stage('Build java project and deploy ') {
            steps {
               git 'https://github.com/Sharath-yp25/java.git'
            }
        }
        stage('compiling the java project ') {
            steps {
               bat '''javac Test.java
                   java Test'''
            }
        }
    }      
