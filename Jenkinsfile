pipeline {
  agent any
  
  stages{
   
    stage("build"){
      steps{
          echo 'building wheel file...........................'
          sh 'python3 setup.py bdist_wheel'
          sh 'cp -r /var/lib/jenkins/workspace/mywheels-pipeline_main/dist/mypackage-0.1-py3-none-any.whl /home/abhinav/jenkins/wheels/'
      }
    }
    
  }
}
