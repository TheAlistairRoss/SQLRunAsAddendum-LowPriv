# SQLRunAsAddendum 7.0.20.1
SCOM - SQL Server RunAs Addendum - Management Pack

https://kevinholman.com/2016/08/25/sql-mp-run-as-accounts-no-longer-required/

* Version 7.0.20.1
Changed frequency of Healthservice SID is Enabled Monitor from 60 seconds to 43200 seconds.
Added On-Demand recalculate capability to Healthservice SID is Enabled Monitor
* Version 7.0.20.0
Added SQL TcpPorts to configuration scripts to enable connecting to secured SQL environments
* Version 7.0.15.2
Updated SQL 2012+ script to remove ALTER ANY DATABASE right, and add SELECT on sql db mirroring tables to fix discovery error when using older MP's
* Version 7.0.15.1
Fixed MP dependencies to support SCOM 2012R2
* Version 7.0.15.0
Original release of the addendum for the SQL Version Agnostic MP for SQL 2012 and later.
