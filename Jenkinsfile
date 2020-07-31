pipeline {
    agent any
    
    stages {
      stage('git clone') {
         steps {
           echo 'git clone'
           git 'https://github.com/prithiviraj123/ansible-sample.git'
           }
           }
      stage('Ansible version') {
         steps {
           echo 'git clone'
           sh 'ansible --version'
         }
         }
      stage('Role Syntax') {
         steps {
           echo 'git clone'
           sh  'ansible-playbook run.yml --syntax-check'
          }
          }
      stage('Execute Role') {
        steps {
          echo 'git clone'
          sh 'ansible-playbook run.yml'
         }
         }

} 
} 








