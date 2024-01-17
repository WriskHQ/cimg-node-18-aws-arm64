First build the docker image:

docker build . --pull --force-rm --tag wrisk/cimg-node-18-aws-arm64

Then, upload the newly built image to the docker repository

docker push wrisk/cimg-node-18-aws-arm64:latest
