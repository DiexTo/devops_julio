pipeline {
    agent any

    stages {
        stage('push') {
            steps {
                echo 'Hello World'
            }
        }
        stage('build'){
            steps{
                echo 'build stage'
            }
        }
        stage('test'){
            steps{
                echo 'test stage'
            }
        }
        stage('deploy'){
            steps{
                echo 'deploy stage'
            }
        }
    }
    post{
        always{
            echo 'ya termine'
        }
        success{
            echo 'todo salio bien'
        }
        failure{
            echo 'algo fallo'
        }
    }
}
