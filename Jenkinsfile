pipeline {
  agent any
  stages {
    stage('deploy') {
      steps {
        copyArtifacts(projectName: 'build.offerings', target: 'deploy.vpc.test')
      }
    }
  }
}