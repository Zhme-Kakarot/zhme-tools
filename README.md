# Tools
Keeping a stash of some of the tools I have made or use regularly for exploitation.

## Ghost Arbitrary File Read Exploit (CVE-2023-40028)
[0xDTC exploit of CVE-2023-40028](https://github.com/0xDTC/Ghost-5.58-Arbitrary-File-Read-CVE-2023-40028/blob/master/CVE-2023-40028)

I had trouble getting this to work, but that was almost certainly a skill issue. I had to extract the general idea from this to
make a script to upload manually. The creds and endpoint are required for the script either way, so I figured I would expedite
the process of testing which files to read so that I could bruteforce aimlessly with more speed.

./cve-2023-40028.sh <path/to/file>

This will create the exploit zip to upload to the target where you find an endpoint in Ghost v5.58.0
The upload section can be found in Settings > Labs

***

