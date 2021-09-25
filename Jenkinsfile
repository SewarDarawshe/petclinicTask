pipeline{
agent any 

stages{

stage('cloning git project'){
steps{
git branch: 'main', credentialsId: 'ea80b490-f30e-4f61-b8b3-426d8202c73e', url: 'https://github.com/spring-projects/spring-petclinic.git'

}
}
stage('enter file'){
steps{

 cd spring-petclinic

}
}
stage('build'){
steps{
echo 'aa'


}

}

} 
}

