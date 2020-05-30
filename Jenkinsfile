#! groovy
@Library('myshared-library@master') _
node('') {
  // prepare checkout
     stage('git checkout') {
          gitCheckout(
            branch: "master",
            url: "https://github.com/rajdeva2009/DevopsProj.git"
       )
      }
}
