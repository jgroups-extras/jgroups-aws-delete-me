# jgroups-aws

JGroups with support for Amazon AWS cloud services. 

No third-party libs required. 

This repo will be sync'd and built with the current master branch of TarantulaTechnology/JGroups, which is sync'd and kept current with the current master branch of belaban/JGroups.

Use repo https://github.com/TarantulaTechnology/JGroups until this mirror repo is initialized with TarantulaTechnology/JGroups.

### New S3 Discovery Protocol

The first AWS cloud service implemented is S3 employing Amazon Authentication Version 4 RESTful API providing access to all AWS regions. Using S3 and the Amazon Authentication Version 4 RESTful API, a new JGroups discovery protocol, S3_PING2 is implemented.



