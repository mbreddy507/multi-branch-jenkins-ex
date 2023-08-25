pipeline {
    agent any
    options {
  buildDiscarder logRotat
  or(artifactDaysToKeepStr: '', artifactNumToKeepStr: '5', daysToKeepStr: '', numToKeepStr: '5')
  disableConcurrentBuilds()
    }

    stages {
        stage ('hello') {
            steps {
                echo 'hello world'
            }
        }
    }
}