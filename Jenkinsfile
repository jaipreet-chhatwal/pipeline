pipeline {
  agent any
  stages {
    stage('Message') {
      steps {
        echo 'Pipeline Init'
      }
    }

    stage('SCM Checkout'){
	
 		git 'https://github.com/jaipreet-chhatwal/pipeline.git'
	}

	stage('Compile-Package'){
	
		sh 'mvn clean package'
	}

  }
}