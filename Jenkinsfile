Pipeline{
	agent any 
	stages{
		stage("run frontend"){
			steps{
				echo 'Executing yarn…'
				nodejs('Node10.17'){
					Sh 'yarn intsall'
				}
			}
		}
		stage("run backend"){
			steps{
				echo 'executing gradle…'
				withGradle(){
					Sh'./gradlew -v' 
        }
     }
   }
 }
}
