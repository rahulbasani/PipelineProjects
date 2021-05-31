pipeline{
    agent any
    stages{
        stage('build'){
            steps{
                echo 'this is build stage';
                sh 'javac hello.java'
            }
        }
        stage('test'){
            steps{
                echo 'this is test stage';
                sh 'java hello'
            }
        }
        stage('deploy'){
            steps{
                echo 'this is deploy stage';
            }
        }
    }
}
