pipeline {
    agent any

    stages {
        stage('Build..') {
            steps {
                sh 'mvn package'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('echo') {
            steps {
                sh 'mvn deploy'
		
            }

	}
	

        }
    }

