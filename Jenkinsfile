pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{
               
           sh 'zip middlewareScript-${BUILD_NUMBER}.zip * --exclude Jenkinsfile README.md'  
            
            }
        }
<<<<<<< HEAD
        
    }
}
 
=======
        stage("test"){
            steps{
                echo "test"
            }
        }
        stage("deploy"){
            steps{
                echo "deploy"
            }
        }
    }
}
 
>>>>>>> 19b8a4f52a0934cd7fbc99cb53c1940ab4b3b6c4
