pipeline {
    agent any

    tools {
        terraform 'terraform'
        maven 'maven'
    }

    stages {
        stage('Checkout') {
                    steps {
                        checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: ]]])
                    }
        }
