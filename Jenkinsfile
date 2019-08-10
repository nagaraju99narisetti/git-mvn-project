node {
stage('SCM Checkout'){
git 'https://github.com/narin004/git-mvn-project'
}
stage ('Compile-package'){
sh 'mvn package'
}
}
