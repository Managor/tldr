# apache2ctl

> Administrate the Apache HTTP web server.
> This command comes with Debian based OSes, for RHEL based ones see `httpd`.
> More information: <https://manned.org/apache2ctl.8>.

- Start the Apache daemon. Throw a message if it is already running:

`sudo apache2ctl start`

- Stop the Apache daemon:

`sudo apache2ctl stop`

- Restart the Apache daemon:

`sudo apache2ctl restart`

- Test syntax of the configuration file:

`sudo apache2ctl -t`

- List loaded modules:

`sudo apache2ctl -M`
