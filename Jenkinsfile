pipeline {
    agent any
    environment {
        PATH = "C:\\Program Files\\MATLAB\\R2019a\\bin;"   // Windows agent
    }
    stages{
        stage('Run MATLAB Command') {
            steps
            {
                runMATLABCommand "apple"
                // Also fails with both statements in 1 line
                // runMATLABCommand 'disp('hello');sim('model1_oneDay')'
            }
        }
    
    }
}
