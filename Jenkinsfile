pipeline {
agent { label 'slave2' }
  parameters{
    choice(name:'number',choices:['1', '2', '3'])
    string(name:'Name',defaultValue:' ')
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
