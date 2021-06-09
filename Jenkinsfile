pipeline {
  agent any
  
  stages{
   
    stage("build"){
      steps{
          echo 'building..........'
          python3 setup.py bdist_wheel
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
