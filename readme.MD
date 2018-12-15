# Node.js with docker deployment

To run this project:
* Download all dependencies of nodejs, run `npm install`
* Build docker image, run `docker build -t node-docker .`
* Run the docket image, run `docker run -d -p 9000:3000 node-docker`

### Application serving on your local machine with port 9000
### Check your IP of docker to see the running application with port 9000