pipeline {
	agent any

	stages {
		stage 'Checkout'
		echo 'Checkout..'
		checkout scm
	}

	stage('Build') {
		steps {
			echo 'Building..'
		}
	}
	stage('Test') {
		steps {
			echo 'Testing..'
		}
	}
	stage('Deploy') {
		steps {
			echo 'Deploying....'
		}
	}
}
}