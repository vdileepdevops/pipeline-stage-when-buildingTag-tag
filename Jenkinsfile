pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				buildingtag()
			}
		
            steps {                
                echo 'Hello World building tag'
            }
        }
    }
}
