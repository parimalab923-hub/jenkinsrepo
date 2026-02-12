pipeline {
  agent any 
  stages {
    stage('working with files') {
      steps {
        script {
          File file = new File("/tmp/file1.txt")
          def lines = file.readLines()
          println "Lines\n ${lines}"
          for(line in lines)
          {
            println line
          }
        }
      }
    }
  }
}
