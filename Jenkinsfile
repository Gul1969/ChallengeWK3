pipeline {
	agent any
	stages {
		stage('Build and test Images'){
			steps {
				sh "./buildscript.sh"
			}
		}
		stage('Run Containers'){
			steps {
				sh "./scripts/run.sh"
			}
		}
	}
}
