pipeline {
  agent any
  stages {
    stage('Test Example Form') {
      steps {
        bat(script: 'C:\\Python27\\python.exe tests\\test_example_form.py -B Chrome', returnStatus: true)
      }
    }
  }
}