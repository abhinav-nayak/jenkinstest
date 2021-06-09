pipeline {
  agent any
  
  stages{
   
    stage("build"){
      steps{
          echo 'building..........'
          sh 'python3 setup.py bdist_wheel'
          sh 'sudo chmod -R 777 /home/'
          sh 'cp dist/* /home/abhinav/Downloads/'
      }
    }
    
    stage("test"){
      steps{
          echo 'testing..........'
      }
    }
    
    stage("deploy"){
      steps{
          echo 'deploying..........'
      }
    }
  }
}
