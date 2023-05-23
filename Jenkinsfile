#!/usr/bin/env groovy
pipeline {
    agent any

    stages {
        stage("Build") {
            steps {
                echo 'building the application'
                sh './shelltest.sh'
            }
        }

        stage("deploy") {
            steps {
                echo 'deploying the application'
            } 
        }
    }
}
