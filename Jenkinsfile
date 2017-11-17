pipeline {
	agent any

	stage 'Checkout'
	echo 'Checkout..'
	checkout scm

	stage('Build')
	echo 'Building..'

	stage('Test')
	echo 'Testing..'
	
	stage('Deploy')
	echo 'Deploying....'
}
