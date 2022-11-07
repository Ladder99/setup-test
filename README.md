# Ladder99 Test Setup

This is an example Ladder99 setup used for testing.

## Running

Do the following to test the pipeline

    cd ~
    mkdir ladder99
    git clone https://github.com/Ladder99/ladder99
    git clone https://github.com/Ladder99/setup-test
    cd ladder99
    ./l99 start test

It may take a while to build and start the first time it's run (eg 10+ mins).

## Dashboard

Then you can visit http://localhost for the Grafana dashboard, which shows the device status. For the first time visiting Grafana use username 'admin', password 'admin', then you will be prompted to change the password. 

## Agent

You can also visit http://localhost:5000/current for the MTConnect Agent UI, which shows the current values for the different dataitems tracked by this setup. 
