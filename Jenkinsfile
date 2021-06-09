pipeline {
  agent any
  
  stages{
   
    stage("build"){
      steps{
          echo 'building wheel file...........................'
          sh 'python3 setup.py bdist_wheel'
          sh 'source="dist/*"'
          sh 'destination="/home/abhinav/Downloads/"'
          sh "scp -r ${source} ${destination}"
      }
    }
    
  }
}
