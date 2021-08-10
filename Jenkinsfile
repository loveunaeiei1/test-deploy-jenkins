pipeline{

  agent { label 'slave-linux' }
  // options
  options {
    timeout(time: 20, unit: 'MINUTES') 
  }
  
  stages{
  
    stage("build") {
    
      steps {
        echo "Only stage Building the application..."
      }
    }
    
  }
}
