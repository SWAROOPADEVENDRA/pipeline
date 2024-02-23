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
                        sh " java demo.java" 
                        sh "python main.py"
                       }
                      }
                  }
             }
        }
