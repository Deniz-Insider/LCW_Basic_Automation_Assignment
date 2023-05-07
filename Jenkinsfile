pipeline {

  agent any
  
  stages {
    stage {
      stage ("build") {
        steps {
            echo "building the test environment"
        }
      }
      
      stage("test") {
        steps {
          echo "running the tests"
        }
      }
      
      stage("deploy") {
        steps {
          echo "deploying the project"
        }
      }
    }
  }

}
