pipeline {
    agent none
    stages {
        stage('Example') {
            agent any
            
            steps {
                echo 'hello Unoveo Ki Janta'
            }
        }
		
		stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
