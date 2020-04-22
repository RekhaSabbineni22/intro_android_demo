
node('docker') {
 
    stage 'Checkout'
        checkout scm
    stage 'Build & UnitTest'
        sh "docker build -t android-build:android-gradle ."
     
 
  
}
