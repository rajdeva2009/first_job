#! groovy
@Library('myshared-library@master') _
node('any') {
  // prepare checkout
     stage('git checkout') {
          gitCheckout(
            branch: "ok",
            url: "https://github.com/rajdeva2009/DevopsProj.git"
       )
      }
}
