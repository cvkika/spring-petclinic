pipeline {
	agent any 
	stages {
		stage ("Install maven")
			{
			agent {
				docker {
					image 'maven'
					}
				}
			steps {
				sh 'mvn clean install'
				}
			}
		}
}
