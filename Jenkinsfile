pipeline {
  agent any
  stages {
    stage('Message') {
      steps {
        echo 'Pipeline Init'
      }
    }

	stage('Compile-Package'){
    	 steps {
    		sh 'mvn clean package'
        }
	 }

  }
}