pipeline{
     agent any
       stages{
         stage("git checkout"){
           steps{
               git url:"https://github.com/Sunil9756/contact_ui_ng_app.git", branch:"main"
         }
         }  
        stage("install node module"){
           steps{
               sh "npm install"
         }
        }
        stage("build"){
           steps{
              echo "image"
              sh "npm run build:ssr" 
         }
        }
        stage(deploy){
           steps{
               echo "push"
               sh "pm2 restart all"
                }   
              }
  }
}
