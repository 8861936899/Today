pipeline {
	agent any
	stages {
		stage('build'){
			steps {
				echo "build script"
				echo "this stage version is build"
				echo "build id is ${BUILD_ID}"
				}
			}
		stage('test'){
			steps {
				echo "test script"
				echo "this environment is test "
				echo "job name is :${JOB_NAME}"
				}
			}
		stage('deploy'){
			steps {
				echo "test script"
				echo "this environment is deploy"
				}	
			
		}
	}
	
}
