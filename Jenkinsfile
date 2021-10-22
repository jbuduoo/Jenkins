pipeline {
    agent any
    tools{
        maven 'mvn-3.8.3'
    stages {
        stage('Hello') {
            steps {
                echo '這是git嗎?'
                echo '我快瘋了'
                echo '誰來救救我'

            }
        }
        stage('Build'){
            steps{
                sh "mvn clean package spring-boot:repackage"
                sh "printenv"
        }
    }
}
