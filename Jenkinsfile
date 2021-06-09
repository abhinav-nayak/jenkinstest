pipeline {
  agent any
  
  stages{
   
    stage("build"){
      steps{
          echo 'building wheel file...........................'
          sh 'python3 setup.py bdist_wheel'
          fileOperations([fileCopyOperation(excludes: '', flattenFiles: false, includes: 'dist/*', targetLocation: '/home/abhinav/Downloads/')])
          echo 'done'
      }
    }
    
  }
}
