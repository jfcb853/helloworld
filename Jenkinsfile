pipeline { 
    agent any  
    stages { 
        stage('Build java 7') { 
            steps {
				withMaven(jdk:'java-7') {
					ss 'mvn clean verify' 
				}
			}
		}
		stage('Build java 8') { 
            steps {
				withMaven(jdk:'java-8') {
					ss 'mvn clean verify' 
				}
			}
		}
	}
}
