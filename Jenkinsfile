pipeline {
    agent any 
    environment {
      JAVA_VERSION = "11.0"
      JAVA_PATH = "/usr/sbin/java"
    }
  parameters {
    choice choices: ['dev ', 'sit', 'uat', 'pt'], name: 'ENV'
    string defaultValue: '1.0.0', name: 'version'
}

    stages {
            stage("welcome to dvs") {
                steps {
                    script {
                        var1=10
                        var2="dvs"
                        println "myvar1 value is ${var1} and myvar2 value is ${var2}"
                        println "my workspace is ${WORKSPACE}"
                        println "my build no is ${BUILD_NUMBER}"
                        println "my java version is ${env.JAVA_VERSION}"
                        println "my java path is ${JAVA_PATH}"
                        println "environment selected is ${param.ENV}"
                        println  "environment  selected is ${params.ENV}"
                        println "version given is ${params.VERSION}"
                    }
                }
            }
        }
    
}
