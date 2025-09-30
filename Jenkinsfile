pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "Building...."
      }
    }

    stage('Unit and Integration Tests') {
      steps {
        echo "Running Unit and Integration Tests...."
      }
    }

    stage('Code Analysis') {
      steps {
        echo "Check the quality of the code....."
      }
    }
    
    stage('Security Scan') {
      steps {
        echo "Scanning for vulnarabilities...."
      }
    }
    
    stage('Deploy to Staging') {
      steps {
        echo "Deploying applicaiton to a staging server....."
      }
    }

    stage('Integration Tests on Staging') {
      steps {
        echo "Running Integration Tests....."
      }
    }

    stage('Deploy to Production') {
      steps {
        echo "Application being deployed..."
        echo "Success!"
      }
    }
  }
}
