pipeline {
    agent { label  "agent1" }
    
    stages {

        stage('Build') {
            steps {
                echo 'Building..'
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing nothing..'
                }
            }
	}

	stage('Deploy') {
            steps {
                echo 'Deploying....'
	
            }
        }  
}  

