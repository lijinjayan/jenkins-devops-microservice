pipeline{

//agent any
agent { docker { image 'maven:3.6.3'} }
stages{

stage('Build') {

steps {
echo "Build Stage"
sh :wq"mvn --version"
}


}

stage('Test') {
steps {

echo "Test"
}


}

stage('DEploy'){
steps { 

echo " Deploy"
}


}
}

}
