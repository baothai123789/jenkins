pipeline{
    agent{
        dockerfile true
    }
    stages{
        stage("test"){
            steps{
                sh node -v
            }
        }
        stage("build") {
            steps{
                sh node index.js
            }
        }
    }
}