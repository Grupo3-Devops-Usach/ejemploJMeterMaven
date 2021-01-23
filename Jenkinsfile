
pipeline
{
    agent any
    stages
    {
        stage('JMeter')
        {
            steps
            {
                    sh 'mvn verify -Pperformance'
            }
        }
    }
 }  
