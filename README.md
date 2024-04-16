First build the docker image:

docker build . --pull --force-rm --tag wrisk/cimg-node-18-aws-arm64

Then, upload the newly built image to the docker repository with the node version tag

docker push wrisk/cimg-node-18-aws-arm64:<node-version-tag>
