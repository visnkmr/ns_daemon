# ns_daemon
NetSpeed Daemon for NetSpeed Overlay app written in Rust that provides 
- the upload, download bytes used of present session 
- total bandwidth usage since the daemon started running. 

Upload and Download total bytes updates every 1s, the total is updated every 60s.

### Crates used
- `serde_json`
- `abserde`
- `serde`
- `chrono`
- `sysinfo `
- `byte-unit `

Tested to work on  
✔️ Manjaro XFCE (Linux, based on Arch)  
  
## Setup:
Tested on Linux but uses libs that should function on Windows and Mac OS platform. Feel free to test in any other platform and tell me the results! You will need Rust installed.

Clone the project and in the same directory open preffered shell and `cargo run <interface-name>(optional)`. You can find the debug executable in `target/debug` folder after running `cargo run`.
  
