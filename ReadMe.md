## Docker Starter
This is a repository with Docker learning materials for beginners. 

### How Docker Works
Docker can build images automatically by reading the instructions from a Dockerfile.
Dockerfile is a text based file that lives locally on the project folder and it contains all the commands a user could call on the command line to assemble an image.

The instructions in a Dockerfile are not case sensitive but the convention is to write them in uppercase in order to differentiate them from arguments.

Dockerfile runs the instructions in order and a Dockerfile must always begin with a FROM instruction. The FROM instruction specifies the Parent Image from which you are building.
