pipeline
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
                        }
             stage("RUN")
                        {
                        steps
                            {
                            sh "python main.py"
                            sh "java demo.java"
                            }
                        }
             }
        }
