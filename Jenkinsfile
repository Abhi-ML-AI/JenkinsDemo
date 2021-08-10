pipeline {
	 agent any 
	 
	 stages {
		stage("compile") {
			steps {
				echo "Compiling"
				bat """ javac Test.java """
				}
			}
			
		stage ("run") {
			steps {
				echo "Running"
				bat """ java Test Hi Everyone"""
				}
			}
			
		}
	}
