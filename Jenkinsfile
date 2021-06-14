pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'echo Integrating Jenkins Pipeline with GitHub Webhook using Jenkinsfile'
            }
	}

        stage('test') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself TEST'
                sh 'echo Integrating Jenkins Pipeline with GitHub Webhook using Jenkinsfile'
            }
        }
	stage ('run'){
	    steps {
	        echo 'clarusway_Way to Reinvent Yourself'
		sh 'python --version'
                sh 'python pipeline.py'
	    }
	}

     }	
}

