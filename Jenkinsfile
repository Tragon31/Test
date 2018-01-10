#!/usr/bin/env groovy

// Jenkinsfile Release de la version

/////////////////////////////////////////////////////////
// Definition de la pipeline Release                   //
/////////////////////////////////////////////////////////

pipeline {
agent { label 'master' }
stages{
   stage("Checkout code")
   {
      steps{
          echo 'Checkout from GitHub'
      }
   }
   stage("Build APP")
   {
      when { expression { 1==0 } }
      steps{
          echo 'Building my APP'
      }
   }
   stage("Deploying Nexus")
   {
      steps{
          echo 'Deploy packages Nexus'
      }
   }
   stage("Install APP")
   {
      steps{
          echo 'Installing my APP'
      }
   }
   stage("Running Tests")
   {
      steps{
          echo 'TNR to verify my APP is working'
      }
   }
 }
}
