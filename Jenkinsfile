pipeline {

  agent any

  stages {
    stage('Build')
    {
      steps {
        echo 'This is a job building stage'
      }
    }

    stage('Test')
    {
      steps {
        echo 'Here, we are running tests'
      }
    }

    stage('Stage')
    {
      steps {
        echo 'This is the staging environment'
      }
    }

    stage('Deploy')
    {
      steps {
        echo 'We are now deploying the finished product'
      }
    }

    stage('Monitor')
    {
      steps {
        echo 'We are now monitoring for any issues/bugs'
      }
    }
  }
}
  
