# rclone-remote-sincronizator

This is just a simple bash script that uses "rclone sync" to replicate a source provider to multiple destination provider

I needed something to be able to sync multiple S3 Buckets for my backups, and this was my solution

# TO-Do
Add alerting system when something goes wrong

# How this thing works
The remotes are added on the REMOTES tuple, with all its configuration, and are created automatically. You can also manually create outside of the script and only provide the name.
The buckets are added on the BUCKETS tuple, the first one the source, the other ones are the destinations

