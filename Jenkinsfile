pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn clean package'
                }
            }
        }

          stage('Test') {
            steps {
                sh 'sleep 30'
            }
        }
        stage('Deploy') {
            steps {
                sh 'sleep 30'
            }
        }
    }
}
