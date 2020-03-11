#!groovy
@Library(['nachshon-jsl@master']) _

def AGENT_GROUP="General"
node(AGENT_GROUP) {

  publishIntelliJPlugin workflowScript: this,
          pluginType: 'wix-intellij',
          releaseType: 'nightly'
}