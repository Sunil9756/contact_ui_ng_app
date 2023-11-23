pipeline{
     agent any
       stages{
         stage(git checkout){
           steps{
             branch:main;
             url:https://github.com/Sunil9756/contact_ui_ng_app.git
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
