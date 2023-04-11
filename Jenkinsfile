//Scripted
// node {
	
// 		echo "Build"
// 		echo "Test"
// 		echo "Test"
	
// }
//Declarative
pipeline {
	agent any
	stages('Build') {
		steps {
			echo "Build"
			
		}
		
	}
	stages('Test') {
		steps {
			echo "Test"
		}
		
	}
	stages('Integration Test') {
		steps {
			echo "Integration Test"
		}
		
	}
}
