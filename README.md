# Memcached cartridge

Memcached 1.4.15 cartridge for openshift.

## Setup
To install to OpenShift from the CLI (you'll need version 1.9 or later of rhc), create your app and then run:

    rhc add-cartridge http://memcached-nv.rhcloud.com/

## Usage
* OPENSHIFT_MEMCACHED_HOST
* OPENSHIFT_MEMCACHED_PORT

This environment variables contains information for connection.

## Memcached tuning
* Create file "your_repo/.openshift/memcached_additional_parameters"
* Write additional parameters ([available parameters](https://code.google.com/p/memcached/wiki/NewConfiguringServer))
* Deploy your application

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

