pipeline {
    agent any
    stages {
        stage('Deploy on Master'){
  agent any
  when{
    branch 'master'
  }
  steps {
    echo 'run this stage - ony if the branch = master branch'
  }
}

stage('Deploy on Dev'){
  agent any
  when{
    branch 'development'
  }
  steps {
    echo 'run this stage - ony if the branch = development branch'
  }
}
    }
}
