pipeline{
	agent any 
	stages{
		stage("run frontend"){
			steps{
				echo 'Executing yarn…'
				nodejs('Node-10.17'){
					sh 'yarn install'
				}
			}
		}
		
        }
     }

