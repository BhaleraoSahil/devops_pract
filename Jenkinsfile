pipeline {
    agent any
    stages{
        stage('index') {
            steps {
                bat 'xcopy /S "*" "C:/xampp1/htdocs/HI" /Y'
            }
        }

        stage('desc'){
            steps {
                bat 'xcopy /S "*" "C:/xampp1/htdocs/hello" /Y'
            }
        }

        stage('info'){
            steps{
                echo 'xcopy /S "*" "C:/xampp1/htdocs/bye" /Y'
            }
        }
    }
}
