pipeline {
  agent {
    docker {
      image 'jenkins/slave'
      args 'docker run -i --rm --name agent --init jenkins/slave java -jar /usr/share/jenkins/agent.jar'
    }

  }
  stages {
    stage('test') {
      steps {
        sh 'echo "working"'
      }
    }

  }
}