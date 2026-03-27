# siem-integration-connector-packages
This is a repo for Akamai SIEM Integration connector packages, previously hosted on developer.akamai.com

For more information, please visit: https://techdocs.akamai.com/siem-integration/docs/akamai-siem-integration-for-splunk-and-cef-syslog#connectors-and-tools

Akamai has signed the CEF Connected binary with a SHA256 hash.
CEFConnector-1.7.13.zip should have a SHA256 hash of 12845f9dd479a3185914ade13ff913deeaa48d87c8e3c7b59d80c4b3b1a26ca9

To verify SHA-256 checksum, run the command:

For Windows: certutil -hashfile [file location] SHA256. <br/>
For example: `certutil -hashfile C:\Users\user1\Downloads\CEFConnector-<version>.zip SHA256`

For Linux: sha256sum [file location]. <br/>
For example: `sha256sum ~/Downloads/CEFConnector-<version>.zip`

For Mac OS: shasum -a 256 [file location]. <br/>
For example: `shasum -a 256 ~/Downloads/CEFConnector-<version>.zip`

The command line returns the file's checksum.
