pipeline {
  agent any 
  stages {
    stage('working with files') {
      steps {
        script {
          File file = new File("/tmp/file1.txt")
          println file.readLines()
        }
      }
    }
  }
}
