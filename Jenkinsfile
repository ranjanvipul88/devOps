pipeline {
  agent any
    stages {
      stage ("build"){
        echo "Build started"
        echo "Build finished"
      }
      stage ("test"){
        echo "Testing started"
        echo "Testing finished"
      }
      stage ("deploy"){
        echo "Deploy started"
        echo "Deploy started"
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

    
