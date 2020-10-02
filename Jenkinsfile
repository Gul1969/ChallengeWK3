pipeline {
	agent any
	stages {
		stage('Build'){
			steps {
				sh "./buildscript.sh"
			}
		}
		stage('Test'){
			steps {
				sh "./buildscript.sh"
			}
		}
		stage('Push'){
			steps {
				sh "./pushscript.sh"
			}
		}
	}
}
