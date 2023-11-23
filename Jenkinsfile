pipeline{
     agent any
       stages{
         stage(git checkout){
           steps{
             branch:main;
             url:https://github.com/Sunil9756/contact_ui_ng_app.git
         }
        stage(build){
           steps{
            sh "mvn clean package"
         }
        stage(image){
           steps{
            sh "docker build -t imagename"
         }
        stage(){
           steps{
               echo "push"
                }   
     }
  }
}
