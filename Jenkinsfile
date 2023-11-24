pipeline
{
    agent any
    stages
    {
        stage ('git hub url')
        {
            steps {
             git branch: 'main', url: 'https://github.com/saisuresh8179/Dynamic-application.git'
            }
        }
        
        stage ('mvn package')
        {
            steps {
                sh ''' mvn clean install '''   
            }
            
        }
    }
}
