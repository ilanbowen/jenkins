node('ops-school-dynamic-slave'){
	currentBuild.result = "SUCCESS"
	stage('checkout'){
		sh 'echo "checkout"'
	}
	stage('unit test'){
		sh 'echo "unit test"'
	}
	stage('integration test'){
		sh 'echo "integration test"'
	}
	stage('deploy'){
		sh 'echo "deploy"'
	}	
}
