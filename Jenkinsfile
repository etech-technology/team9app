pipeline{
	agent any 
	stages{
		stage('1-start'){
			steps{
				checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'new_id', url: 'https://github.com/etech-technology/team9app1.git']])
			}
		}
		stage('2-johnst'){
			steps{
				echo "make a left"
			}
		}
		stage('3-michael park'){
			steps{
				echo "cross the street"
				echo "stop when you see walmart"
			}
		}
		stage('4-walmart'){
			steps{
				echo "enter walmart and start shopping"
			}
		}
		stage('5-closing argument'){
			steps{
				echo "we are closing here"
			}
		}
	}
}