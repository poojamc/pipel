pipeline {
agent { label 'slave2' }
  parameters{
    choice(name:'number',choices:['1', '2', '3'])
    string(name:'num1',defaultValue:' ')
    string(name:'num2',defaultValue:' ')
  }
stages {
stage('add') {
steps {
  sh 'echo addition of ${num1} and ${num2} is {$num1 + $num2}'
}
}
  stage('test') {
steps {
sh 'echo this is test'
}
}
}
}
