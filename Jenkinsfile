pipeline {
    agent any

    stages {
        stage('write out powershell file') {
            steps {
                powershell '.\\Powershell\\HelloWorld.ps1'
            }
        }
        stage('Stage2') {
            steps {
                echo "Hello World"
            }
        }
    }
}
