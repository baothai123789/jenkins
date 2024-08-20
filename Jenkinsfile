pipeline{
    agent{
        docker {image 'node:20.16.0-alpine3.20'}
    }
    stages{
        stage("test"){
            steps{
                sh 'node -v'
            }
        }
        stage("build") {
            steps{
                sh 'node index.js'
            }
        }
    }
}
