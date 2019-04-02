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
                //export PATH=$PATH:~/usr/local/make
                export PATH=$PATH
                pwd;
                cd ../make;
                pwd;
                make;
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

