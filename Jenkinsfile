pipeline {
    agent any 
    stages {
        stage('Stage 1 CHECKOUT') {
            steps {
                println '======= Checkout ========'
                echo 'Pulls down relevant repos' 
            }
        }
        stage('Stage 2 BUILD API') {
            steps {
                println '======= Build ========'
                echo 'Uses template/provisioning tools to create environments' 
            }
        }
        stage('Stage 3 TEST') {
            steps {
              println '======= Test ========'
                echo 'task: Unit Test'
                echo 'task: Smoke Test' 
                echo 'task: End-to-end Test'  
            }
        }
        stage('Stage 4 DEPLOY') {
            steps {
              println '======= Deploy ========'
                echo 'Deploys EC2 instances for use' 
            }
        }
        stage('Stage 5 CLEANUP ') {
            steps {
              println '======= Clean ========'
                echo 'Clean stage' 
            }
        }
        
    }
}