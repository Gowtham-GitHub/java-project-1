pipeline { 
    agent any
    stages { 
         stage ("SCM Chkout-1"){ 
              steps { 
                   git 'https://github.com/Gowtham-GitHub/java-project-1' 
              } 
         } 
         stage ("Java execute"){ 
              steps { 
                   sh 'javac code.java'
                  sh 'java Simple'
              } 
         } 
    } 
}
