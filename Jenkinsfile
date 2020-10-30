pipeline {
  agent any
  stages {
    stage('make python script'){
      steps{
       //make the file
        sh "chmod +x ./make-python.sh"
        sh "./make-python.sh"
        //sh 'touch helloworld.py'
        }
    }
    stage('run python script'){
      steps{
       //run the script
        python3 helloworld.py
      }
    }
  }
  
}
