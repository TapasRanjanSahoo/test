pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
                echo 'code checkout done'
            }
			}
		stage('maven build') {
            steps {
                echo 'maven build done'
            }
			}
        stage('sonar analysis') {
            steps {
                echo 'sonar analysis done'
            }
			}
        stage('war configuration') {
            steps {
                echo 'war configuration done'
            }
			}
			
        stage('deployment') {
            steps {
                echo 'deployment done'
            }
			}
         stage('mail notification') {
            steps {
                echo 'mail notification done'
            }
			}
			
        }
    }
