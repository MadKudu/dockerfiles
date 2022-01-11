# See list https://github.com/CircleCI-Public/circleci-dockerfiles/blob/master/node/images/
FROM circleci/node:14-bullseye

# Install python + pip
RUN sudo apt-get update
RUN sudo apt-get install build-essential zlib1g-dev libssl-dev libncurses-dev libffi-dev libsqlite3-dev libreadline-dev libbz2-dev python3-pip python3 python-dev 
RUN sudo pip3 install --upgrade virtualenv
RUN sudo pip3 install --upgrade requests
# Install the EB CLI
RUN pip3 install awsebcli --upgrade --user
RUN export PATH=~/.local/bin:$PATH
# Install rsync
RUN sudo apt-get install rsync
