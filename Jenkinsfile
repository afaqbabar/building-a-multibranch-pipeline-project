pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello from Build Environment"'
            }
        }
        stage('Deploy - Dev') {
            steps {
                deploy('dev')
            }
        }

    }

//steps
}

def deploy(environment) {


   sh 'echo "Hello from Dev Environment"'

}



