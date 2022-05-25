//declarative
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Build"
            }
        }
        stage('Test') {
            steps {
                echo "Test"
            }
        }
        stage('Integration Test') {
            steps {
                echo "Integration Test"
            }
        }

    } 
	post {
		always {
			echo 'im awesome. I run always'
		}
		success {
			echo 'Im awesome. Im super fast'
		}
		failure {
			echo 'I run when you are superior fast'
		}
	}

}

 
