pipeline{
agent any
stages{
stage('Build application'){
steps{
bat 'mvn clean install'
}
}
stage('Deploy mule application in cloud'){
steps{
bat 'mvn package deploy -DmuleDeploy'
}
}
}
}
