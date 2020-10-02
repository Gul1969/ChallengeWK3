pipeline {
	agent any
	stages {
		stage('Build Images'){
			steps {
				sh "./buildscript.sh"
			}
		}
		stage('Build Images'){
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
