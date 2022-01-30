node{
   stage('Code Pull')
   {
   git branch: 'main', url: 'https://github.com/Akanksha-001/devops-210940120010'
   }
   stage('Code Compile')
   {
   sh 'javac helloworld.java'
   }
   stage("Execute Code")
   {
   sh 'java helloworld'
   }
}
