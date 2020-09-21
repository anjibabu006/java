node()
{
    stage('ContinuousDownload') 
    {
         git 'https://github.com/anjibabu006/java.git'
    }
    stage('ContinuousBuild') 
    {
         sh label: '', script: 'mvn package'
    }

    
    
}

