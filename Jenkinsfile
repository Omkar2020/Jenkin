@Library('my-shared-lib') _

pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Test Shared Library') {
            steps {
                sayHello 'Omkar'
            }
        }
    }
}
