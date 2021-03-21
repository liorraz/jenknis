#!/usr/bin/env groovy
pipeline {
    agent {
        docker { image 'python' }
    }

    stages {
        stage("Run tests") {
            steps {
                echo "*******testing************"
                sh 'python --version'
            }
        }
    }
}
