pipeline {
  agent any
  
  stages{
   
    stage("build"){
      steps{
          echo 'building wheel file...........................'
          sh 'make wheel'
          sh 'pwd'
          sh 'cp -r /var/lib/jenkins/workspace/mywheels-pipeline_main/dist/mypackage-0.1-py3-none-any.whl /home/abhinav/jenkins/wheels/'
      }
    }
    
  }
}
