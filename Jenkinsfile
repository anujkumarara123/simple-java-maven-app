pipeline{

agent any

stages{
stage('Hello'){
steps{
echo "hello"
}
}
stage('cat readme'){
when {
branch "fix-*"
}
steps{
sh '''
cat README.md
'''
}

}
}

}
