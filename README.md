# starlink.deploy
mup deployment script

#### SSH to starlink.io server
    chmod 400 StarLink.pem
    ssh -i StarLink.pem ubuntu@starlink.io

#### Setup Meteor on starlink.io server
    mup setup

#### Deploy starlink application to starlink.io server
    mup deploy

#### other mup commands
    mup reconfig
    mup logs -f
    mup start
    mup stop
    mup restart
