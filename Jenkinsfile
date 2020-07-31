pipeline {
    agent any
    
    stages {
      stage('git clone') {
         steps {
           echo 'git clone'
           git 'https://github.com/prithiviraj123/ansible-sample.git'
           }
           }
           stages {
             stage('git clone') {
                steps {
                  echo 'git clone'
                  git 'https://github.com/dineshSOSU/devops-react-3.git'
                 }
                 }
      stage('Ansible version') {
         steps {
           echo 'git clone'
           sh 'ansible --version'
         }
         }
      stage('AWS connectivity') {
         steps {
           echo 'git clone'
           sh 'aws s3 ls'
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








