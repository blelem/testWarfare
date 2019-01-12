Testing a Jenkins setup, using a barebone node server.
   From : https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/skeleton_website

To Install:
   npm install

To start the server:
   SET DEBUG=theTestMachine:* & npm run devstart

Starting the Jenkins ssh connection:
  ssh -L 127.0.0.1:8080:localhost:8080 XXX@eatech-jenkins-test.northeurope.cloudapp.azure.com
  
Setting up Jenkins pipeline :
   https://medium.com/@gustavo.guss/jenkins-starting-with-pipeline-doing-a-node-js-test-72c6057b67d4
   
   
 
