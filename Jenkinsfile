pipeline {
    agent any
    stages {
        stage('TEST') {
            agent{
    	    	label 'master'
    		}
            steps {
                echo 'Hello master'
            }
        }
        stage('TEST5') {
            agent{
    	    	label 'linux172'
    		}
            steps {
                 echo 'Hello linux172'
            }
        }
    }
    
}
