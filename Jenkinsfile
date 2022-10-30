pipeline{
    agent any
    stages{
        stage("git checkout"){
            when{
                branch "devlop"
            }
            steps{
                echo "hello world"
            }
        }
        stage("stage2"){
            when{
                branch "staging"
            }
            steps{
                echo "hello bro"
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
