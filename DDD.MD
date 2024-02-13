RevSpring did not receive file from mainframe

SFTP Automated process is not working 

In mainframe you will see Abend on job  CFFSNDNS 

Below report is available in RMDS

<img width="428" alt="Capture" src="https://githubcloud.deere.com/storage/user/1960/files/f02fbab1-eb6e-40d1-9977-6e53560576cd">

Make Sure zip file is created at \\\\fgriftp1\\Oakville InfoLease\\FTP\\Prod\\InfoLease\\Letters

With name as Letxxxdd\.zip

XXX\- Month name \(for eg JUL\),dd\-Date of file when NSencrypt process executed

Make a copy of the file rename it as JDCXXXDD\.zip\(naming  format in mainframe\)

XXX\- Month name \(for eg JUL\),dd\-Date of file

SFTP Credentials:

Hostname: ftpx\.revspringinc\.com

User and Password found in Kee Pass

The new SFTP site address is [ftpx\.revspringinc\.com](http://ftpx.revspringinc.com) and they must use SFTP, port 22 or they can access via the internet using [https://ftpx\.revspringinc\.com/](https://ftpx.revspringinc.com/)

Please send Live, Production files\- JDCXXXDD\.zip to the ‘IN’ folder

