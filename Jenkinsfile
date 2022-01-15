pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
                sh "echo Hello from the shell"
                echo scm.branches[0].name
            }
        }
    }
}