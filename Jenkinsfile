pipeline{
  agent any{
    triggers {
    githubPush()
  }
    stages{
      stage('build')
      {
        echo 'Building'
        echo 'hello'
      }
      stage('test')
      {
        echo 'testing'
      }
    }
  }
}
