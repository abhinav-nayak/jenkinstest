pipeline {
  agent any
  
  stages{
   
    stage("build"){
      steps{
          echo 'building wheel file...........................'
          sh 'python3 setup.py bdist_wheel'
          sh 'pwd'
          sh 'cp /var/lib/jenkins/workspace/mywheels-pipeline_main/dist /* /home/abhinav/jenkins/'
      }
    }
    
  }
}
