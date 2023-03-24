pipeline {
  agent any
  parameters {
    string (
      name: 'BUILD_ENVIRONMENT',
      defaultValue: 'dev',
      description: 'Environment profile used for current dev'
    )
  }
  stages {
    stage('Hello stage') {
      steps {
        echo 'Hello World from patching ${params.BUILD_ENVIRONMENT}'
       }
    }
  }
}
