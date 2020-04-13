pipeline{
agent any
stages{
stage('Build application'){
steps{
bat 'MVN clean install'
}
}
stage('Deploy mule application in cloud'){
steps{
bat 'MVN package deploy -DmuleDeploy'
}
}
}
}
