pipeline {

    agent any
    
    stages {
        stage('Checkout'){
            steps{
                git branch:'master',url:'https://github.com/harikrishnan99-tech/jenkins-example.git'
            }
        }
        stage('Compile stage') {
            steps {
                bat "mvn clean compile" 
        }   }
    

        stage('testing stage'){
            steps{
                 bat "mvn test"
            }
        }
           
        
    }

         

}
