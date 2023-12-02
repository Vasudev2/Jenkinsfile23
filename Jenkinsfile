node {
    stage('Code Clone') {
      git credentialsId: 'git', url: 'https://github.com/Vasudev2/example.git'
     }
    stage('Code Clean') {
      sh 'mvn clean'
     }
    stage('Code Validate') {
      sh 'mvn validate'
     }
   stage('Code Compile') {
     sh 'mvn compile'
     }
   stage('Code Test') {
     sh 'mvn test'
     }
   stage('Code Package') {
     sh 'mvn package'
     }
