pipeline {
    agent any

    stages {
        stage('NPM intsall') {
            steps {
               bat 'npm install '
            }
        }
         stage('Run tests') {
            steps {
               bat 'npm run  test'
            }
        }
    }
}
