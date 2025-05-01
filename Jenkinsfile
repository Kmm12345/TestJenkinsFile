pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git ''
                script {
                    sh 'git config user.email "kmagill1995@gmail.com"'
                    sh 'git config user.name "Jenkins Job -TestPowershellPipeline"'
                }
            }
        }
        stage('write out powershell file') {
            steps {
                powershell '.\\Powershell\\HelloWorld.ps1'
            }
        }
        stage('Stage3') {
            steps {
                echo "Hello World"
            }
        }
    }
}
