# ns_daemon
NetSpeed Daemon for NetSpeed Overlay app written in Rust that provides 
- the upload, download bytes used of present session 
- total bandwidth usage since the daemon started running. 

Upload and Download total bytes updates every 1s, the total is updated every 60s.
