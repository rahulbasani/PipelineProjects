pipeline{
    agent any
    stages{
        stage('build'){
            steps{
                echo 'this is build stage';
                javac 'hello.java'
            }
        }
        stage('test'){
            steps{
                echo 'this is test stage';
            }
        }
        stage('deploy'){
            steps{
                echo 'this is deploy stage';
            }
        }
    }
}
