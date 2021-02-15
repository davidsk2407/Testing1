pipeline {
	agent any
    stages {
        stage('Build') {
            steps {
                bat "rmdir /s /q Testing1"
                bat "git clone https://github.com/davidsk2407/Testing1.git/" 
                bat "start cmd.exe /c cd /d C://Users/david/OneDrive/Desktop/Main_Testing/BCN - Build Engineer test/BCN - Build Engineer test/build-engineer-test/CoolGame/run.bat"
                }
            }
        }
    }
