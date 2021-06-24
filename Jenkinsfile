pipeline {
    agent any 
    tools
    {
        maven "MAVENHOME"
    }
    stages
    {
        stage('Build')
        {
            steps{echo 'Build'
                //git 'https://github.com/SreedeviPK/poc1.git'
                //sh "mvn clean install"
                //bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }
           /* post{
                success{
                    junit '**target/surefire-reports/TEST-*.xml'
                    archieveArtifacts 'target/*.jar'
                }
            }*/
        } 
    }
    
    
    /*stages {
        stage('Static Analysis') {
            steps {
                echo 'Run the static analysis to the code' 
            }
        }
        stage('Compile') {
            steps {
                echo 'Compile the source code' 
            }
        }
        stage('Security Check') {
            steps {
                echo 'Run the security check against the application' 
            }
        }
        stage('Run Unit Tests') {
            steps {
                echo 'Run unit tests from the source code' 
            }
        }
        stage('Run Integration Tests') {
            steps {
                echo 'Run only crucial integration tests from the source code' 
            }
        }
        stage('Publish Artifacts') {
            steps {
                echo 'Save the assemblies generated from the compilation' 
            }
        }
    }*/
}
