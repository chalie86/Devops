pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is tshifhiwa'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
            stage('Deploy Post Production') {
                  steps {
                        echo "Deploying in Production  postArea"
                  }
            }
            stage('Deploy in Staging Environment') {
                  build job: 'Deploy_Application_Staging'
                  }
            }
      }
}