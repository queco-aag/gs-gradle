
pipeline {
agent any
  tools {
    gradle "gradle-local"
  }
stages {
stage('Build') {
steps {
sh 'echo Fase Build;sleep 7;echo Fase Build Terminada'
  sh 'gradle --version'
}
}
stage('Test'){
steps {
sh 'echo Fase Test;sleep 17;echo Fase Test Terminada'
}
}
stage('Deploy') {
steps {
sh 'echo Fase Deploy;sleep 10;echo Fase Test Deploy'
}
}
}
}

