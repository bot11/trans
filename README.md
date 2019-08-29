# trans
A middleware library

The core idea is to implement a tier3 middleware server, which relies on unix system calls. This transaction server can forward the requests to any of the underlying T3 servers(databases/ldap..etc).

The implementation will be in golang. Should be pluggable to make multiple T3 systems connected to the server based on a yaml configuration file.

Will look at scaling in future.
