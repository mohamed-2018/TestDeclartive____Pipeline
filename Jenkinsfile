pipeline 
{
    agent any
    stages
    {
        stage('SCM CHECKOUT')
        {
            steps
            {
                echo 'SCM COMPLETED'
            }
        }
        stage('Build')
        {
            steps
            {
                echo 'Build COMPLETED'
            }
        }
        stage('Test')
        {
            steps
            {
                echo 'Test COMPLETED'
                sh 'date'
            }
        }
        stage('Deploy')
        {
            steps
            {
                echo 'Deploy COMPLETED'
            }
        }
    }
}
