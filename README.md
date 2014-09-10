## Manage database backups for ProcessWire

[Read this blog post about this module](https://processwire.com/blog/posts/august-2014-core-updates-4/#database-backups-module)

This tool provides an admin interface for the following database backup functions: 

- Creating new backups
- Uploading backups
- Restoring backups
- Providing info on existing backups
- Managing existing backups (downloading, deleting, etc.)

This is meant to be used as a secondary backup tool, not a primary one. It uses
ProcessWire 2.5 WireDatabaseBackups class to perform backups and restores. If 
you are working with really large files, it may be better to perform that task
directly in PhpMyAdmin or the native MySQL client. 

Requires ProcessWire 2.4.14 or newer.

---

Copyright 2014 by Ryan Cramer

