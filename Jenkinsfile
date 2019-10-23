#!groovy
pipeline {
    agent {
        node {
            label 'plesk18 && windows2019'
            customWorkspace "${env.CUSTOM_WORKSPACE_ROOT}\\${env.JOB_NAME}"
        }
    }
}