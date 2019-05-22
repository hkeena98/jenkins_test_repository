
//Jenkinsfile (Declarative Pipeline)

pipeline {
    agent any
    stages {
        stage('Start') {
            steps {
                input('Do you wish to compile the program?')
            }
        }
        stage('Compile') {
            steps {
                echo 'Compiling the code...'
                sh 'javac JenkTest.java'
                echo 'Code compiled...'
            }
        }
        stage('Run') {
            steps {
                echo 'Running Java Code...'
                sh 'java JenkTest'
            }
        }
    }
}

