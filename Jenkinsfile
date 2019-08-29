    
pipeline{
	agent any
    stages{
		stage('---deploy---'){
			steps{
				sh "docker stack deploy --compose-file docker-compose.yaml project-skyre"
			}
		}
	}
}
