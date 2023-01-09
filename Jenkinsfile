pipeline{
    
    agent any

    stages {

        stage('Git Checkout'){

            steps{
                    git branch: 'main', url: 'https://github.com/khalidbaddi/mvn.repo.git'
                }
            }
        stage('Unit Test'){

            steps{
                    sh 'mvn test'
                }
            }
        }
    }
