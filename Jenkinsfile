@Library("sneha-shared-library") _
import com.hexaware.sharedlib.SharedLibrary
def sharedLibrary = new SharedLibrary(this)
pipeline {
  agent any
  stages {
    stage ('Shared Library') {
      steps {
        script {
          sharedLibrary.startBuild()
        }
      }
    }
  }
}
