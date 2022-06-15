peline {
    agent { docker { image 'maven:3.8.4-openjdk-11-slim' } }
    stages {
	stage('copiando'){
		steps{
		  sh 'mkdir nome_build'
                  sh 'cp /* nome_build' 
		}
	}
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
