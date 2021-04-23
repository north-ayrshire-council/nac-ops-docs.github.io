# RunBook / Manual

*RunBook / System Operation Manual*.


## System overview

*SYSTEM NAME*

### NAC Service overview

> What does this system do?

### Service owner

> Which team owns this system - contact details

### System Tech Stack

> What Platform, Database, Middleware, etc does it use?

### System Users

> What are the system user details?

## Interfaces

> How does data flow through the system?

_(e.g. cron jobs / scheduled jobs )_

### Infrastructure

> List server names, network, etc?


### DR / Failover plans

> What happens in a disaster?

### Start and stop

> How do you start / stop all or part of the system?


### Environment

> Production and other test envs?
_

### Tools / scripts

> What tools /scripts are available to help manage this system?


### Resources

> What compute, storage, database, etc are needed? Min / Max - CPU cores, Memory, storage etc


## Backup and restore

### Backup

> What is backed up?

_(e.g. database, binaries, etc)_

### Backup procedure

> Does the system need shutdown? Backup tool?

_(e.g. ZFS snapshot, Commvault, etc)_

### Restore procedure

> What is the restore procedure?

_(e.g. Does it need authorised? Technical process steps)_

## Monitoring and Alerting

### Logs

> Where are the logs?


### Monitoring tool

> What monitoring tool is used?

_(e.g. vROPs, Solarwinds, etc)_

### Automated email alerts

> What automated emails will be triggered?


## Operational tasks

### Batch processing

> What kind of batch processing takes place?

_(e.g. Files are pushed via SFTP. Interfaces?)_


### Troubleshooting

> What should my initial troubleshooting steps be?


## Maintenance tasks

### Patching

> When and how are patches deployed?

### Data clean-up

> What data needs cleaned-up? When does this occur? 

 
### Log management

> Are logs rotated? How is this done? 




[Thanks to SkeltonThatcher](https://github.com/SkeltonThatcher/run-book-template) for inspiring this template and hopefully kicking off team discussion.
[Skelton Thatcher Consulting](https://skeltonthatcher.com/)

Licenced under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) ![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/3.0/88x31.png)

