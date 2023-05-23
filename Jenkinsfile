#!/usr/bin/env groovy
pipeline {
    agent any

    stages {
        stage("Build") {
            steps {
                echo 'building the application'
                sh /c/Users/weichong.liong/Desktop/GIT_scripts_DM
            }
        }

        stage("deploy") {
            steps {
                echo 'deploying the application'
            } 
        }
    }
}
