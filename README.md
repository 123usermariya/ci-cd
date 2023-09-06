# ci-cd
Steps involved:
1. Launched EC2 instance
2. Connect the EC2 instance and install docker, git, and Jenkins on it.
3. Configure Jenkins on the server.
4. After configuration, create a freestyle job on Jenkins.
5. Configure the job ( Source code management: paste the URL of the repository and add the credential of GitHub) and then click on "Build now".
6. Create a Dockerfile and Expose it at Port 8000 then edit the inbound rule and allow it anywhere.


