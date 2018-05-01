<h3>How to use cmd-test</h3>

1. clone or download <b>cmd-test</b> on your system.
2. open terminal or cmd and change directory to the cmd-test folder.
3. Execute the following command to create a Docker image from the Dockerfile.

    <b>sudo docker build -f Dockerfile -t adder-java . </b>
    
    Don't miss the <b>. dot</b> at the end, it represents the context path to be used by the Docker for creating the image. 
    
4. Run the image in a container as follows:
   
   <b>sudo docker run adder-java </b>
   
   The output should be: <b> Sum is 30</b> because the default values of command line arguments in the <br/> Dockerfile are
   <b>CMD ["10", "20"]</b>
   
4. Run the image again by overriding the <b>CMD</b> arguments as follows:
   
   <b>sudo docker run adder-java 40 50</b>
   
   The output should be: <b> Sum is 90</b> 
   
 <h3>Thats it! you have learned the use of <b>CMD</b> command in a Dockerfile. </h3>   
   
<b> Note: Don't use sudo in windows.</b>
 
 
