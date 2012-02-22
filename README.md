This is the Pivotal Casebook hobson worker config. hobson workers are redis workers and look for jobs on a central redis server.

Our hobson fork: https://github.com/Casecommons/hobson, branch `casebook` 

### Installation

Clone this repo, then

    cd hobsonworker
    # accept and install any rvm stuff
    gem install bundler
    bundle --without debug19

### Configuration
See `config.yml` and the readme for `hobson.yml` at https://github.com/Casecommons/hobson

Pay special attention to the URL for the redis server. This is where all hobson workers will get their jobs.

### Runing a Worker

    bundle exec hobson work 
