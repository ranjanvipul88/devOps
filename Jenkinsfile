pipeline {
  agent any
    stages {
      stage ("build"){
        steps{
        echo "Build started"
        echo "Build finished"
        }
      }
      stage ("test"){
        steps{
        echo "Testing started"
        echo "Testing finished"
        }
      }
      stage ("deploy"){
        steps{
        echo "Deploy started"
        echo "Deploy started"
        }
      }
    }
    post {
      always {
        echo "Post-always executed"
      }
      success {
        echo "Post-success executed"
      }
      failure {
        echo "Post-failure executed"
      }
    }
}

    
