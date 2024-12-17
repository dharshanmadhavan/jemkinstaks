pipeline{
    agent any
    stages{
        stage("execute"){
            steps{
                sh './file1.sh'
                sh 'cat file1.sh'
                }
        }
        stage("execute1"){
            steps{
                sh './file2.sh'
                sh 'cat file2.sh'
                }
        }
       

    }
}
