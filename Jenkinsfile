pipeline{
     agent any
       stages{
         stage("git checkout"){
           steps{
             git url:"https://github.com/Sunil9756/contact_ui_ng_app.git", branch:"main"
         }
         }  
        stage(build){
           steps{
            echo "build"
         }
        }
        stage(image){
           steps{
            echo "image"
         }
        }
        stage(push){
           steps{
               echo "push"
                }   
              }
  }
}
