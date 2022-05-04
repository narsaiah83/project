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
        stage('Deploy') {
            steps {
                sh 'mvn deploy'
<<<<<<< HEAD
            }
=======
		}
	
>>>>>>> a6366484dc17aa8967f2fb93909ced449910beed
        }
    }
}
