pipeline {
	node {
		agent any
		
		stage('checkout')
		checkout scm

		stage('build')
		sh 'echo hello,world'
	}
}