pipeline {
    agent any
    stages{
        stage('check-out'){
            steps{
                git branch: 'main', url: 'https://github.com/msahanagowda/GitRepo' /*repository is public*/
            }
        }
        
        stage('file1'){
            steps{
                bat 'file1.bat'
            }
        }
        stage('file2'){
            steps{
                bat 'file2.bat'
            }
        }
        stage('file3'){
            steps{
                bat 'file3.bat'
            }
        }
    }
}
