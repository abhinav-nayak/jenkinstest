pipeline {
  agent any
  
  stages{
   
    stage("build"){
      steps{
          echo 'building wheel file...........................'
          sh 'python3 setup.py bdist_wheel'
          sh 'chmod 777 /home/abhinav/Downloads/'
          sh "cp dist/* /home/abhinav/Downloads/"
          echo 'done'
      }
    }
    
  }
}
