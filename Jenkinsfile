pipeline{
    agent any
    stages{
        stage("git checkout"){
            when{
                branch "devlop"
            }
            steps{
                git url "https://github.com/Bawgi778/varma"
            }
        }
        stage("stage2"){
            when{
                branch "staging"
            }
            steps{
                sh "mvn clean package"
            }
        }
        stage("stage3"){
            when{
                branch "master"
            }
            steps{
                echo "hello multi"
            }
        }
    }
}
