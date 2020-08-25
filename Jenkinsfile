pipeline {
    agent any
    tools {
        maven 'M2_HOME'
    }    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
          stage('build') {
            steps {
                echo 'hello build'
                sh 'mvn clean'
                sh 'mvn install'
                sh 'mvn package'
            }
        }
          stage('deploy') {
            steps {
                echo 'Hello World'
            }
        } 
        stage('test') {
            steps {
                echo 'Hello World'
            }
        }
    }
}

