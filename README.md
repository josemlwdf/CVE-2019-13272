[+] [CVE-2019-13272] PTRACE_TRACEME

   NOTE: This python3 version of the exploit DOES NOT REQUIRE any external source. The sources that follows are just credits for the original exploit in C.

   Details: https://bugs.chromium.org/p/project-zero/issues/detail?id=1903
   
   Exposure: highly probable
   
   Tags: ubuntu=16.04{kernel:4.15.0-*},ubuntu=18.04{kernel:4.15.0-*},debian=9{kernel:4.9.0-*},[ debian=10{kernel:4.19.0-*} ],fedora=30{kernel:5.0.9-*}
   
   Download URL: https://github.com/offensive-security/exploitdb-bin-sploits/raw/master/bin-sploits/47133.zip
   
   ext-url: https://raw.githubusercontent.com/bcoles/kernel-exploits/master/CVE-2019-13272/poc.c
   
   Comments: Requires an active PolKit agent.
