pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps { checkout scm }
        }
        stage('Hello') {
            steps { echo 'Hello from a Jenkinsfile stored in Git!' }
        }
	stage('Hello Number 2'){
	    steps { echo 'Hello from a Jenkinsfile stored in Git! version 2' }
	}
    }
}
