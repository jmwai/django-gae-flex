## Django on App-Engine Flex

This project is based on [cookiecutter-django](https://github.com/pydanny/cookiecutter-django) and demonstrates how to run a typical Django web application on Google App-Engine Flexible Environment, previously know as Managed VMs. The project will demostrate the following:
- GAE Flex Project structure Configuration
- Storing data on Cloud SQL and
- Storing and serving media and static files from Cloud Storag
- Caching data - using memcache service
- Queuing and messaging - using Task queues and Cloud Pub/Sung
- Logging and monitoring - using stackdriver
- Deployment
- Scaling
- Testing (Using travis)


#TODO: only one week left

sort out the cloud sql and be comfortable demoing it.
sort out cloud storage and be comfortable demoing it.
Work on memcache as a service
Work on Task Queuing with cloud pub sub
integrate stackdriver



so 3 major components that I need to do

#Cloud Memcache
#Cloud Pub/Sub
#Stack Driver

A day for each and two days for the others(db,storage,)

Two days for fine tuning the demo and slides

total 7 days



Lagos day one morning:
Skygarden payments test sandbox
working cloud sql and storage for gae app.

day two morning

skygarden payments implementation
integrate cloud memcache for the gae app

day three morning
test akygarden payments integrations
integrate cloud pub/Sub

Nairobi on Monday:
Integrate stack Driver

Nairobi tuesday wednesday:
fine tune presentation with kenju

the above is tough but i think it's doable


The idea is to show how you can easily run your django app on GAE just like you
would on aws by taking advantage of many services that django needs you to configure and maintain
but are offered as services on google cloud
these are database, file storage, caching, task Queuing, Logging
all these are available as services on the google cloud.


SLides agenda

appe engine managed vms intro
storing data on gcp
caching data on gcp
queing tasks on gcp
monitoring logs on gcp
