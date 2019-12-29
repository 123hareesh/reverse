node {
 	// Clean workspace before doing anything
    deleteDir()

    try {
        stage ('Clone') {
        	checkout scm
        }
        stage ('Build') {
        	echo "add build steps here"
        }
        stage ('Tests') {
	       
	          echo 'shell scripts to run static tests...'
	        
            }
      	stage ('Deploy') {
                 echo 'shell scripts to deploy to server...'
      	}
    } 
	catch (err) {
                echo 'some error '
    }
}
