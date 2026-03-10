pipeline agent{
  agent any
  stages{
    stage('DEV'){
      steps{
        echo 'Development Stage'
      }
    }
    stage('QA'){
    steps{
      input "Deploy to QA?"
    }
    }
    stage('DEPLOY TO PROD'){
    steps{
      bat 'xcopy index.html C:\\apache-tomcat-11.0.18\\webapps\\ROOT /E /I /Y
    }
    }
  }
}
