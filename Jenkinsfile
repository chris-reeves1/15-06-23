pipeline {
    agent any
    stages{
        stage("make directory"){
        steps {
            sh "mkdir ~/jenkins-test-demo" || true
        }
    }
    stage ("add a file") {
        steps {
            sh "touch ~/jenkins-test-demo/file1"
        }
    }
}
}
