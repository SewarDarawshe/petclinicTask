
pipeline{

agent { label 'slave' } 

stages{

stage('cloning git project'){
steps{
git branch: 'main', credentialsId: 'ea80b490-f30e-4f61-b8b3-426d8202c73e', url: 'https://github.com/spring-projects/spring-petclinic.git'
cd spring-petclinic
}
}
}
stage('build'){
steps{
script{



"./mvnw package"
}
}

}

} 
}

