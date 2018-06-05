pipeline {
    agent any 
    stages {
	stage('Run'){
	    steps {
		sh 'nohup npm start &'
		}
	}
    }
    post{
	success {
            echo 'Ran successfully'
        }
        failure {
            echo 'Error occured'
        }
        unstable {
            echo 'This will run only if the run was marked as unstable'
        }
     }
}
