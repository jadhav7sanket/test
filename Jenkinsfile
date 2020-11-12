pipeline{
  stages{
    steps {
                script {
                    def output = sh (
                        script: "java -version",
                        returnStdout: true
                    ).trim()
                    assert output == '11' || '8'
                }
           }
        }
        }
