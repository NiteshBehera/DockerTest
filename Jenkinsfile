pipeline{
	agent { dockerfile true }
	stages{
		stage('build image'){
			steps{
			sh "docker build -t docker-image-test:$BUILD_NUMBER ."
		      }
		}
	}
}
