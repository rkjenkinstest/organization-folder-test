pipeline {

  environment {
    registry = "rkjenkinstest/organization-folder-test"
  }

  agent any

  stages {

    stage('Checkout Source') 
	{
      steps {
        git 'https://github.com/rkjenkinstest/organization-folder-test.git'
			}
    }
	
	stage('echo Success') 
	{
    steps {
        echo 'Code checked out successfully'
      }
    }
  }
}
