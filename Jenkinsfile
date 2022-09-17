pipeline{

    agent {
        dockerfile {
            filename  'Dockerfile'
            args  '--privileged'
        }      
    }
    
    stages{
        stage('Build') {
            steps{
                sh 'ls -al /usr/bin'
            }
        } 
    }    
}
