pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                
                bat "start C:\\Users\\DH\\Downloads\\Test_Code\\alert_03.html" 
                echo 'Hello World'
            }
        }
        stage('Deploy') {
            steps {
                bat "start C:\\Users\\DH\\Downloads\\Test_Code\\alert_02.html"
                echo 'Deploy ing'
            }
        }
        stage('Test') {
            steps {
                bat "start C:\\Users\\DH\\Downloads\\Test_Code\\alert_04.html"
                echo 'Test ing'
            }
        }
        stage('Release') {
            steps {
                bat "start C:\\Users\\DH\\Downloads\\Test_Code\\alert_01.html"
                echo 'Release ing'
            }
        }
    }
}
