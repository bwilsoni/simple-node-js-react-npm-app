pipeline {
    agent any
    // agent {
    //     docker {
    //         image 'node:6-alpine' 
    //         args '-p 3000:3000' 
    //     }
    // }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
        stage('Echo') {
            steps {
                echo 'Hello There'
            }
        }
    }
}