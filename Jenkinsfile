pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                bat 'npm install'
                script {
                    powershell '''
                        Write-Output "Hello world"
                        $date = Get-Date
                        Write-Output "Write current date" $date
                    '''
                }
                script {
                    powershell '''
                        C:\\Untitled1.ps1
                    '''
                }
            }
        }
    }
}