#!groovy 

node { 
  def mvnHome 
  stage('Preparation') { 
  
    git 'https://github.com/daniel19942015/desafio-indra.git' 
    mvnHome = tool 'M3' sh 'cd users\Henrique\env\Scripts'
  
  }
  stage('Build') {
    echo 'BUILD' 
  } 

  stage('Results')  { 
    echo 'Results' 
  } 
}
