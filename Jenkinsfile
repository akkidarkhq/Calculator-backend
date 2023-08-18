pipeline {
    agent any
	tools{
		maven 'Maven 3.9.3'
	}
    stages {
        stage('Example') {
            agent any
            
            steps {
                echo 'hello Unoveo Ki Janta'
            }
        }
		
		stage('Build') { 
            steps {
                sh 'mvn  package' 
            }
        }
    }
}
