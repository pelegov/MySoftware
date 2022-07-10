pipeline{
agent any
stages {
  stage('checkout'){
steps{
      git 'https://github.com/pelegov/MySoftware.git'
     }
  }
  stage('build') {
steps{
      sh 'python /Users/nave-peleg/PycharmProjects/MySoftware/TestForConflict.py'
      }
        }
      }
}
