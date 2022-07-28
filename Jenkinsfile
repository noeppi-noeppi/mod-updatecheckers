#!/usr/bin/env groovy

pipeline {
    agent any
    tools {
        jdk 'java17'
    }
    stages {
        stage('Generate') {
            steps {
                echo 'Building'
                sh './gradlew generate'
            }
        }
    }
}
