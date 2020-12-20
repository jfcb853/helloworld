pipeline { 
    agent any  
    stages { 
        stage('Build java 8') { 
            steps {
				withMaven(jdk:'java-8') {
					sh 'mvn clean verify' 
				}
			}
		}
	}
}
