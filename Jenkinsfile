pipeline {
    agent {docker
    {image 'alpine:3.7'}}
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') {
            steps {
                echo 'Creating infrastrcture'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application on staged environment'
            }
        }
    }
}
