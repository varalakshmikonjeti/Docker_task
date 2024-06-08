pipeline 
     {
      agent any
      }
      stages
      {
       stage('git')
       {
        steps
            {
              git "https://github.com/varalakshmikonjeti/Docker_task.git"
              }
}
        stage('run')
        {i
         steps
            {
             sh "shell.sh"
             sh "python3 python.py"
             }
        }
       
      }//stages
      }//pipeline
