pipeline{
        agent any
        stages{
            stage('Make Directory'){
                steps{
                    sh "mkdir ~/jenkins-tutorial-test"
                }
            }
            stage('Make Files'){
                steps{
                    sh "touch ~/Jenkins-with-Docker/file1 ~/Jenkins-with-Docker/file2"
                }
            }
        }
}