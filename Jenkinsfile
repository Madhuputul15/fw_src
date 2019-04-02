#!/bin/sh
/*export PATH=$PATH:~/usr/local/make
pwd;
cd ../make;
pwd;
make;*/

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..................'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing....................'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...................'
            }
        }
    }
}

