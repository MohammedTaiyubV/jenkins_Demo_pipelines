pipeline{
    agent any
    stages{
        stage("Execute"){
            steps{
                 bat 'java Fact.java'
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
