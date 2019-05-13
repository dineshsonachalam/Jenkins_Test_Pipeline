pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                echo 'Building'
            }
        }
        stage('test') {
        	steps{
        		echo 'Testing'
        	}
        }
        stage('deploy') {
        	steps{
        		echo 'Deploying'
        	}
        }
    }
}

