pipeline
{
    agent any
    
   environment 
    {
        dotnet ='C:\\Program Files (x86)\\dotnet\\'
    }
        
    stages
    {
    stage('Build')
    {
        steps
            {
                bat "dotnet build C:\\Users\\vanimohanrlab\\SrcCode\\YummyRestuarant\\YummyRestuarant\\TestCoreWebApplication.csproj --configuration Release"
            }
    }
    stage('Publish')
    {
        steps
            {
                bat "dotnet publish  C:\\Users\\vanimohanrlab\\SrcCode\\YummyRestuarant\\YummyRestuarant\\TestCoreWebApplication.csproj "
            }
    }
    }
 }