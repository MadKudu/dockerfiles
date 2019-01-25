# See list https://github.com/CircleCI-Public/circleci-dockerfiles/blob/master/node/images/
FROM circleci/node:10.14.1-browsers
MAINTAINER MadKudu (www.madkudu.com)

RUN sudo apt-get install python-pip python python-dev build-essential
RUN sudo pip install --upgrade pip
RUN sudo pip install --upgrade virtualenv
RUN pip install awscli --upgrade --user
RUN pip install awsebcli --upgrade --user
RUN export PATH=~/.local/bin:$PATH
