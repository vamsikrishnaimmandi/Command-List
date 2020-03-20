#!groovy
import groovy.json.JsonSlurperClassic
node
{

//def BUILD_NUMBER=env.BUILD_NUMBER
//def RUN_ARTIFACT_DIR="tests/${BUILD_NUMBER}"
def SFDC_USERNAME="AkiAndPawpaw@scratchorg.com"

stage('checkout source')
{
    // when running in multi-branch job, one must issue this command
    checkout scm
  echo ${SFDC_USERNAME}
}
}
