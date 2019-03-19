node('JenkinsSlave2'){
	currentBuild.result = "SUCCESS"
	stage('checkout'){
		sh 'echo "checkout"'
	}
	stage('unit test'){
		sh 'python home-assignments/session2/exercise1.py --city dublin --forecast TODAY -c'
	}
	stage('integration test'){
		sh 'echo "integration test"'
	}
	stage('deploy'){
		sh 'echo "deploy"'
	}	
}
