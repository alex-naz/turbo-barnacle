# Repository for SCIFM0004- Distributed Computing Mini-project
Contains all the files needed to build and operate the data processing application. <br>
Build the application: <br>
Ensure the Docker Engine is running <br>
"docker build -f Dockerfile1 -t process:1.0 ." <br>
"docker build -f Dockerfile2 -t plot:1.0 ." <br>
<br>
Run the application: <br>
"docker compose up" <br>
"docker run -v assessments_data_all:/input -v C:/Users/Alexander/Documents/scicomp/assessments:/output plot:1.0" <br>
<br>
*For the /output file path, enter the desired location on the host's filesystem. If using a Windows PC, make sure to switch the brackets from backwards slashes to forwards slashes as in the example above.
