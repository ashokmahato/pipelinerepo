node {
   stage('checkout') {
   //git([url: 'git@github.com:ashokmahato/pipelinerepo.git', branch: 'master', credentialsId: 'ec2-priv-key'])
     checkout scm
   echo " dummy echo"
   sh('cat $HOME/mytest.txt')
   }
  }
