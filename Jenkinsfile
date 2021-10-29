pipeline {
    agent any

    

    stages {
        stage('Cloning From Git') {
            steps {
              git branch: 'main', url: 'https://github.com/Pranali14932/GradleBuildTestDemo.git'
            }
        }
        stage ('Build') {
    	    steps {
    	        sh 'chmod +x gradlew'
	        	sh './gradlew clean build'
        	}
         }
         
    }
}
