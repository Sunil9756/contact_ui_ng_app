pipeline{
     agent any
       stages{
         stage("git checkout"){
           steps{
             ech "url"
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
