pipeline {
   agent any
   environment {
       PATH = "C:\\Program Files\\MATLAB\\R2020a\\bin;${PATH}"   // Windows agent
    // PATH = "/usr/local/MATLAB/R2020a/bin:${PATH}"   // Linux agent
    // PATH = "/Applications/MATLAB_R2020a.app/bin:${PATH}"   // macOS agent    
   }
    stages{
        stage('Run MATLAB Command') {
            steps
            {
               runMATLABCommand "disp('Hello World!')"
            }       
        }                
    } 
}
