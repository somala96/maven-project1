pipeline {
    agent any

    stages {
        stage('Dev') {
            steps {
                echo 'Hello-Dev-Stage'
                build quietPeriod: 3, job: 'job1'
            }
        }
        stage('Test') {
            steps {
                echo 'Hello Test-stage'
                build quietPeriod: 3, job: 'job2'
            }
        }
        stage('Prod') {
            steps {
                echo 'Hello Prod-stage'
                build quietPeriod: 3, job: 'job3'
            }
        }
    }
}
