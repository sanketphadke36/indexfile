pipeline {
          agent {
		  label {
		  label "built-in"
          customWorkspace "/mnt/git"		  
		  }
		  }

stages {

        stage ("install-httpd") {
		steps {
		sh "cp index.html /var/www/html"
			sh "chmod -R 777 /var/www/html/index.html"
		
		
		}
		
		}


}



}
