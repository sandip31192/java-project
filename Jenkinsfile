pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                sh 'mvn -DshipTests clean package'
            }
        }
        stage("Test"){
            steps{
                sh 'mvn test'
            }
        }
    }
    
    
}




