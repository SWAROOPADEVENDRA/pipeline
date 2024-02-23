Pipeline
        {
       agent any
          stages
                {
                stage("GIT")
                     {
                     steps
                          {
                           git "https://github.com/SWAROOPADEVENDRA/pipeline.git"
                          }
                  stage("Run")
                       {
                       sh "python3 main.py"
                       sh " java demo.java" 
                       }
                      }
                  }
             }
        }
