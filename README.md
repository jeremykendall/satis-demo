Satis Demo
==========

Satis demo to accompany Composer presentations

## Usage
* `git clone git@github.com:jeremykendall/satis-demo.git`
* `cd satis-demo`
* `composer create-project composer/satis --stability=dev --keep-vcs`
* `cp satis-config.json satis/config.json`
* `cd satis`
* `php bin/satis build config.json web/`
* Use `sample-vhost.conf` to set up your local Satis site
* Add `127.0.0.1    satis.dev` to your `/etc/hosts'
* Restart apache
* `cd ../project`
* Run `composer install`
* Composer will install dependency from local Satis server
* WIN
