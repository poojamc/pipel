pipeline {
agent { label 'slave2' }
  parameters{
    choice(name:'number', choice:['1', '2', '3'])
  }
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
