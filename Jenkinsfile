pipeline {
    agent {
       node {       
          label 'Devnode'
      }
    }
    stages {
        stage('Deploying to Dev_test server') {
            steps {
                script { 
                    sh """
                      ls /home/centos
                      hostname
                      whoami
                      
                       """
             }
   		   }
		}
       }
    }
