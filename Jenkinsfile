pipeline {
  agent any
  stages {
    stage('Message') {
      steps {
        echo 'Pipeline Init'
      }
    }

    stage('SCM Checkout'){
    	  steps {
          git 'https://github.com/jaipreet-chhatwal/pipeline'
      }
	}

	stage('Compile-Package'){
    	 steps {
    		C:\Windows\system32\cmd.exe 'mvn clean package'
        }
	 }

  }
}