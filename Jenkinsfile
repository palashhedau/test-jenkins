pipeline {
    agent any 
    stages {
	stage('Run'){
	    steps {
		sh ' lolnpm start'
		}
	}
    }
    post {
      
        success {
            echo 'Success'
        }
        failure {
            echo 'Error occured'
        }
        
    }
}
