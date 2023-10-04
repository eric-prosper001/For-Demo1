pipeline{
	agent any
	stages{
		stade('1-clonecode'){
			steps{
				sh 'action1'
			}
		}
		stage('2-artifactbuild'){
			steps{
				sh 'df -h'
			}
		}
		stage('3-unitest'){
			steps{
				sh 'lscpu'
			}
		}
        stage('4-deploy'){
			steps{
				echo "we are on pipeline code module"
			}
		}
	} 
		
	}

}