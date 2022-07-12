pipeline {
	agent any 
	stages {
		stage ("Install maven")
			{
			agent {
				docker {
					image 'maven:3.5.0'
					}
				}
			steps {
				sh 'mvn clean install'
				}
			}
		}
}
