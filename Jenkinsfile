pipeline {
    
    agent any 
    
    stages {
        stage('SCM') {
            steps {
                echo "I am SCM"
                sh 'date'
                git branch: 'main', url: 'https://github.com/santoshgaikwad2024/Jenkins_training_Docker.git'
            }
        }
		
        stage('Build') {
            steps {
                echo "I am Build"
                echo 'date'
            }
        }
		
        stage('Test') {
            steps {
                echo " I am Test"
            }
        }
        
        stage('Deploy') {
            steps {
                echo " I am Deploy"
            }
        }
    }

}
