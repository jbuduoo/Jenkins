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
        stage('TEST2') {
            steps {
                 echo 'Hello TEST2'
            }
        }
        stage('TEST3') {
            steps {
                 echo 'Hello TEST3'
            }
        }
        stage('TEST4') {
            steps {
                 echo 'Hello TEST4'
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
