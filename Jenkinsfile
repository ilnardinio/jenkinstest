pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
                sh 'ls -l'
                dir ('foo') {
                    writeFile file:'dummy', text:''
                }
                sh 'ls -l'
            }
        }
    }
}
