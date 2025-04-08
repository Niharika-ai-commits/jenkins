pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "echo This is build"
            }
        }
        stage('Test') {
            steps {
                sh "echo This is test"
            }
        }
        stage('Deploy') {
            steps {
                sh "echo This is deploy"
            }
        }
    }
}
post {
    always{
        echo "This sections always runs"
    }
    sucess{
        echo "This section runs when pipelines sucess"
    }
    failure{
        echo "This section runs when pipeline fails"
    }
}
