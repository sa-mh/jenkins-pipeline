pipeline {
  agent any
  stages {
    stage('make python script'){
     //make the file
      sh 'touch helloworld.py'
      // put content in file
      sh 'echo "print('hello world')" > helloworld.py'
    }
    stage('run python script'){
     //run the script
      python3 helloworld.py
    }
  }
  
}
