//Scripted
// node {
	
// 		echo "Build"
// 		echo "Test"
// 		echo "Test"
	
// }
//Declarative
pipeline {
	agent any
	stages{
	stage('Build') {
		steps {
			echo "Build"
			
		}
		
	}
	stage('Test') {
		steps {
			echo "Test"
		}
		
	}
	stage('Integration Test') {
		steps {
			echo "Integration Test"
		}
		
	}}
	post{
		always{
			echo 'I run always'
		}
		success{
			echo 'I run when you are sucessful'
		}
		failure{
			echo 'I run when you fail'
		}
	}
}
