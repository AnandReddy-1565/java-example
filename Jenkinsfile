pipeline{
	agent { label 'tomcat'}
	stages{
        stage('Build stage') {
            steps {
                echo 'build stage'
				sh 'sleep 5'
			}
		}
        stage('Push stage') {
            steps {
                echo 'This is push stage'
                sh 'sleep 5'
			}
		}
        stage('Deploy stage') {
            steps {
                echo 'This is deploy stage'
                sh 'sleep 5'
			}
		}
	}
}	
