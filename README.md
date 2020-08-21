A simple, customisable table audit system for PostgreSQL11 implemented using triggers w/ JSONB and partitioning support.

See Original Trigger for usage as they are the same.:

http://wiki.postgresql.org/wiki/Audit_trigger_91plus


This fork differences vs 91plus.
- Uses JSONB instead of HSTORE
- Automatically creates partitioned tables by month (Requires PG11).
