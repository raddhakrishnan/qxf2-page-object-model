pipeline {
  agent any
  stages {
    stage('Qxf2: POM') {
      parallel {
        stage('Test Example Form') {
          steps {
            bat(script: 'C:\\Python27\\python.exe tests\\test_example_form.py -B Chrome', returnStatus: true)
          }
        }
        stage('Test Example Table') {
          steps {
            bat(script: 'C:\\Python27\\python.exe tests\\test_example_table.py -B Chrome ', returnStatus: true)
          }
        }
      }
    }
  }
}