node('slave2') {
   
    stage('checkout') { 
        git 'https://github.com/praveenkumar1290/rock-paper-scissors.git'
    }
	stage('build'){
	sh 'mvn package'
	}
	stage('test'){
	sh 'mvn test'
	}
	stage('print today date'){
	sh 'date'
	}
    
}
  


