# Docker Base Image Testing
This is a spike repository for figuring out what best practices should be for
testing the Base Docker images that application images will be built from.

This uses the Goggle [Container Testing Framework](
https://github.com/GoogleContainerTools/container-structure-test) to run the 
tests.

Steps to run tests using this project:

1. Install Dependencies:
    - Docker
    - Container Testing Framework Binary or Image (see above link)
1. Build the test image (commands from root directory of this project)
    - `cd test_image`
    - `docker build . -t test-image`
1. Run the tests
