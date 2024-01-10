pipeline {
  agent: any

  stages {
    stage("Test") {
      steps {
        withPythonEnv('python3') {
            sh """
                echo "BRANCH: ${param.BRANCH}"
            """
        }
      }
    }
  }
}
