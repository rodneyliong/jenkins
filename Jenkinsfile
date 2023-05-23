#!/usr/bin/env groovy
pipeline {
    agent any

    stages {
        stage("Build") {
            steps {
                echo 'building the application'
				sh C:\Users\weichong.liong\Desktop\GIT_scripts_DM\shelltest.sh
				
            }
        }

        stage("deploy") {
            steps {
                echo 'deploying the application'
            } 
        }
    }
}