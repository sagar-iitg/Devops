
```

pipeline {
    agent any

    stages {
        
        stage('Code ') {
            steps {
              
              echo "Cloning from github"
              git url:'https://github.com/sagar-iitg/Jenkins-Project-Node.git', branch:'master'
                
                
            }
        }
        stage('Build'){
             steps {
              
                
            echo "Building Code"
                
            }
            
        }
        stage('Test'){
             steps {
              
            echo "Testing the new build"
                
                
            }
            
            
        }
        stage('Deploy'){
             steps {
              
                   echo "Deploying to the production"
                
            }
         
            
        }
        
    }
}


```
