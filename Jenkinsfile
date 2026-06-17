pipeline{
  agent any
  stages{
    stage("Print hostname"){
      steps{
      sh "hostname"
      }
    }
    stage("Print Private IP address"){
      steps{
        sh "hostname -I"
      }
    }
    stage("Disk space usuage"){
      steps{
        sh "df -h"
      }
    }
  }
}
