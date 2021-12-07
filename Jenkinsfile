node('maven-3.8.4')
{
    stage('scm'){
        git branch: 'scripted', url: 'https://github.com/gitforpractise/javarepo.git'
    }
    stage('package')
    {
        sh 'mvn clean package'
    }
}

