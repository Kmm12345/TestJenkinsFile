pipeline {
    agent any

    stages {
        stage('write out powershell file') {
            steps {
                powershell '.\\Powershell\\HelloWorld.ps1'
            }
        }
    }
}
