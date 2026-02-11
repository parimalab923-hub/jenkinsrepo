def myfunction() {
println "hi i am new dev"
}
def myfunctionwithparams(a,b) {
sum = a + b
println "add of a & b is ${sum}"
}
pipeline {
    agent any 
        stages {
            stage("welcome to dvs") {
                steps {
                    script {
                        myfunction()
                        myfunctionwithparams(10,20)
                    }
                }
            }
        }
    
}


