pipeline {
    agent any
    stages{
        stage('build') {
            steps {
                sh 'echo "Hello World" > hello.txt'
            }
        }
	stage('archive') {
            steps {
                archiveArtifacts artifacts: 'hello.text', followSymlinks: false)
            }
        }
    }
}
