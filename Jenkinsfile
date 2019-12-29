node {
 	// Clean workspace before doing anything
    deleteDir()

    try {
        stage ('Clone') {
        	//checkout scm
        }
        stage ('Build') {
        	sh label: '', script: 'echo \'shell scripts to deploy to server...\''
        }
        stage ('Tests') {
	       
	            sh "echo 'shell scripts to run static tests...'"
	        
            }
      	stage ('Deploy') {
            sh "echo 'shell scripts to deploy to server...'"
      	}
    } 
	catch (err) {
        sh "echo 'some error ' "
    }
}
