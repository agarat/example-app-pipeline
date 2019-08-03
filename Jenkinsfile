@Library('jenkins-shared-library') _

pipeline {
    agent any
    stages {
        /*stage('SonarQube analysis') {
            steps {
                container('sonar-scanner') {
                    // requires SonarQube Scanner 2.8+
                    withSonarQubeEnv('Sonar') {
                        sh '''
                            sonar-scanner \ 
                            -Dsonar.projectKey=agarat_example-app-pipeline \
                            -Dsonar.organization=agarat-github \
                            -Dsonar.sources=.
                        '''
                    }
                }
            }
        }*/
        stage('Using shared library') {
            testMySharedLibrary
        }
    }
}
