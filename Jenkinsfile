pipeline {
    agent {
        docker {
            image 'maven'
        }
    }

    stages {
        stage('Hello') {
            steps {
                sh '''
		   mvn -version
		   cat f2.txt
		'''

            }
        }
    }
}
