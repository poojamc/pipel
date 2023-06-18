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
  sum={$num1+$num2}
  sh 'echo addition of ${num1} and ${num2} is $sum'
}
}
  stage('test') {
steps {
sh 'echo this is test'
}
}
}
}
