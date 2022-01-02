pipeline {
  agent any
  stages {
  stage('Build') {
    steps {
      // One or more steps need to be included within the steps block.
      echo "Building .."
      withMaven(maven: 'maven') {
         sh 'cd my-app;mvn compile;java -cp target/classes com.mycompany.app.App'
      }
    }
  }

  stage('Test') {
    steps {
      // One or more steps need to be included within the steps block.
      echo "Testing .."
    }
  }

  stage('Deploy') {
    steps {
      // One or more steps need to be included within the steps block.
      echo "Deploying .."
    }
  }

}

}
