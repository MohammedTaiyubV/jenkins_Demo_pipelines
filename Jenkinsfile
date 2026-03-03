pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                javac Fact.java
                echo "Compile  success"
            }
        }
        stage("Execute"){
            steps{
                java Fact
                echo "Execute Success"
            }
        }
        stage("Deploye"){
            steps{
                echo "Deploye success"
            }
        }
        
    }
}
