pipeline{

    agent {
        dockerfile true
        args "--privileged"
    }
    stages{
        stage('Build') {
            steps{
                sh 'ls -al /usr/bin'
            }
        } 
    }    
}
