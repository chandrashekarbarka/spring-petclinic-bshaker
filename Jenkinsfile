node {
    stage('SCM') 
    {
        git url: 'https://github.com/chandrashekarbarka/spring-petclinic-bshaker.git',
            branch: 'main'
    }
    stage('Build')
    {
        sh '''
        mvn clean package
        '''
    }
}
