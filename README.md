# Repository for SCIFM0004- Distributed Computing Mini-project
Contains all the files needed to build and operate the data processing application. <br>
Build the application:
- Ensure the Docker Engine is running
- "docker build -f Dockerfile1 -t plot:1.0 ."
- "docker build -f Dockerfile2 -t process:1.0 ."
Run the application:
- docker compose up
- docker run -v assessments_data_all:/input -v C:/Users/Alexander/Documents/scicomp/assessments:/output plot:1.0
*For the /output file path, enter the desired location on the host's filesystem. If using a Windows PC, make sure to switch the brackets from "\" to "/" as in the example above.
