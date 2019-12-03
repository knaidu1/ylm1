node('master')
{
  stage('naid++++++++uContinuousDownload')
  {
    git 'https://github.com/selenium-saikrishna/maven.git'
  }
  stage('ContinuousBuild')
  {
    sh 'mvn package'
  }
}
