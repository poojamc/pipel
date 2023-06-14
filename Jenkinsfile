pipeline {
agent { label 'slave2' }
stages {
stage('checkout') {
steps {
sh 'echo this is checkout'
}
}
  stage('test') {
steps {
sh 'echo this is test'
}
}
}
}
