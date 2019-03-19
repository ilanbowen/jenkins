node('JenkinsSlave2'){
	currentBuild.result = "SUCCESS"
	stage('checkout'){
		sh 'echo "checkout"'
	}
	stage('unit test'){
		sh 'exit 1'
	}
	stage('integration test'){
		sh 'echo "integration test"'
	}
	stage('deploy'){
		sh 'echo "deploy"'
	}	
}
