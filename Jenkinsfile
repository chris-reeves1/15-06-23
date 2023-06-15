pipeline {
    agent any
    stages{
        stage("make directory"){
        steps {
            sh "mkdir ~/jenkins-test-demo"
        }
    }
    stage ("add a file") {
        steps {
            sh "touch ~/jenkins-test-demo/file1"
        }
    }
}
}
