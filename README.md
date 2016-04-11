# boxes-contrib

A collection of scripts extracted from [boxes][]. It's mostly intended for bits
which don't quite fit in the main project.

## Scripts

* `ruby.sh`: Installs [chruby][], [ruby-install][] and a common set of Ruby
  version.
* `postgres.sh`: Installs [Postgres][], configured access to local addresses
  and creates a default user (`vagrant`, with a password of `vagrant`).
* `mysql.sh`: Installs [MySQL][], configured access to local addresses
  and creates a default user (`vagrant`, with a password of `vagrant`).


## Author

Copyright (c) 2015 Nick Charlton <nick@nickcharlton.net>.

[boxes]: https://github.com/nickcharlton/boxes
[chruby]: https://github.com/postmodern/chruby
[ruby-install]: https://github.com/postmodern/ruby-install
[Postgres]: http://www.postgresql.org
[MySQL]: http://www.mysql.com
