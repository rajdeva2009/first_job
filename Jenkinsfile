node('') {
  echo "GitHub BranhName ${env.BRANCH_NAME}"
  
  stage('checkout') {
    git branch: 'master',url: 'https://github.com/rajdeva2009/first_job.git'
  }
  
  stage('data') {
    sh "echo ${WORKSPACE}"
  }
}
