# MIKEY-SAKKE
Some people may be looking for Mikey-Sakke specifically by name so I created this page.

Mikey is primarily just a transport mechanism (one of a number that could be used to transport ECCSI/ SAKKE information). The __clever stuff__ Signing/ Verification of messages using ECCSI (Elliptic Curve-Based Certificateless Signatures for Identity-Based Encryption) and the Encryption/ Decryption of an SSV (Shared Secret Value) using SAKKE, is covered in the ECCSI-SAKKE project below. 

To generate Key Material for Mikey-Sakke clients (for whatever the flavour of Mikey-Sakke stack you decide upon) the KMS project listed below can be referenced.

ECCSI-SAKKE
-----------
For code that does ECCSI Sign/ Verify (RFC 6507) and SAKKE Encrypt/ Decrypt (RFC 6508 and parts of 6509), refer to:

  https://github.com/jim-b/ECCSI-SAKKE

KMS
---
For KMS (Key Management Server) code, that generates Mikey-Sakke Key Material that clients can use, refer to:

  https://github.com/jim-b/KMS
  
Other implemntators
-------------------
If you're generally looking at open source Mikey-Sakke implementations, you may also consider:

  https://securechorus.org

and at their code at:

  https://bitbucket.org/securechorus/workspace/repositories
