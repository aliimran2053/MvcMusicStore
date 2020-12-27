pipeline{
	agent any        //can run on any available jenkin agent , could be a node , it means  run on next available agent
	stages{
		stage("build"){
			steps{
				echo "building app"  //scrit command for building app like npm install , command run on jenkuns agent
				//if javasscript app
				//sh 'npm install'
				//sh 'npm build'
			}
		}
		
		stage("test"){
			steps{
				echo "testing app"
			}
		}
		stage("deploy"){
			steps{
				echo "deploying app"
			}
		}
	}
}