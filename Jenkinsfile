pipeline{
    agent{
        label 'my-docker-agent'
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
