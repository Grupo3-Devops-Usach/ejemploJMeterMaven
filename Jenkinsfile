pipeline
{
    agent any
    stages
    {
        stage('JMeter')
        {
            steps
            {
                    echo 'Compile Code ...'
                    sh 'mvn verify -Pperformance'
            }
        }
    }
 }  
