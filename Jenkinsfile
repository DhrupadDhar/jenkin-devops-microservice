// Scripted
// node {
// 	stage('Build') {
// 		echo "Build"
// 	}
// 	stage('Test') {
// 		echo "Test"
// 	}
// 	stage('Integration Test') {
// 		echo "Integration Test"
// 	}
// }

//Declarative
pipeline {
	agent any
	stages{
		stage('Build') {
			steps{
		echo "Build"
			}
		}
		stage('Test') {
			steps{
		echo "Test"
			}
		}
		stage('Integration Test') {
			steps{
		echo "Integration Test"
			}
		}
    }
}