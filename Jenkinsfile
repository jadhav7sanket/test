pipeline{
  agent any
  stages{
    stage('Test'){
      steps {
                script {
                    def output = sh (
                        script: "java -version",
                        returnStdout: true
                    ).trim()
                    
                }
           }
        }
        }
}
