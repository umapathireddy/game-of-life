pipeline {
  agent any
  stages {
    stage('') {
      steps {
        checkstyle(canComputeNew: true, canResolveRelativePaths: true, canRunOnFailed: true, useDeltaValues: true, usePreviousBuildAsReference: true, useStableBuildAsReference: true)
      }
    }
  }
}