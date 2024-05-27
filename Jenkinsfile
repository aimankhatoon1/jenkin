pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Allication build stage...' 
        }
       }
        stage('Test') {
            steps {
                echo 'Allication test stage' 
        }
        }
        stage('Run') {
            steps {sh'gcloud compute zones list'
                echo 'Allication run stage hellohyyy' 
            }
        }
    }
}
