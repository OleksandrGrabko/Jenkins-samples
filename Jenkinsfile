pipeline {
    agent any

    stages {
        stage('Build from SCM') {
            steps {
                git([url: 'https://github.com/OleksandrGrabko/testrepo.git', branch: 'master'])

                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
