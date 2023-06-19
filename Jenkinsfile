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
      int a = params.num1;
      int b = params.num2;   
      c = a + b;
     echo "sum is ${c}
}
}
   stage('test') {
    steps {
    sh 'echo this is test'
}
}
}
}
