# quickrip - Backup CDs

### WARNING: Archived/unmaintained
## DO NOT USE!!!

This script is a simple wrapper around the cdparanoia tool: You can use it to
rip CDs in a single pass. DVD support may be added later if I still use them
in 2024...

Usage
-----
First, make sure that ```/dev/cdrom``` points to a valid device containing
a CD.
```$ quickrip```

You will be asked to provide for album name, artist name, album year. Then,
the number of tracks with their respective names. Most discs should work
without further issues.

However, there is still a significant number of records (especially pre-2000)
that have poorly formatted disks, for example containing blank tracks in
between of the actual songs.

At that point, you should consider using a more professional tool.

TODO
----
- FLAC conversion
- FLAC tags
