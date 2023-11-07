# siem-integration-connector-packages
This is a repo for Akamai SIEM Integration connector packages, previously hosted on developer.akamai.com

For more information, please visit: https://techdocs.akamai.com/siem-integration/docs/akamai-siem-integration-for-splunk-and-cef-syslog#connectors-and-tools

Akamai has signed the CEF Connected binary with a SHA256 hash.
CEFConnector-1.7.7.zip should have a SHA256 hash of 872501a216090bb0241dcb36febaf7040e8b011388eaf3f2be3330d4c3314449

To verify SHA-256 checksum, run the command:

For Windows: certutil -hashfile [file location] SHA256. <br/>
For example: `certutil -hashfile C:\Users\user1\Downloads\CEFConnector-1.7.7.zip SHA256`

For Linux: sha256sum [file location]. <br/>
For example: `sha256sum ~/Downloads/CEFConnector-1.7.7.zip`

For Mac OS: shasum -a 256 [file location]. <br/>
For example: `shasum -a 256 ~/Downloads/CEFConnector-1.7.7.zip`

The command line returns the file's checksum.
