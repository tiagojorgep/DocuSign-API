# DocuSign-API
Hints to use DocuSign APIs / SDKs

Enable API
-------------

1) At DocuSign console, go to "Admin > API and Keys"
2) Create a new integration key by clicking in "ADD APP / INTEGRATION KEY"
3) Give a name to your integration key
4) Check option "Implicit Grant"
5) Generate a RSA keypair by clicking in "ADD RSA KEYPAIR"
6) Save the keypair generated at a safe place. 
   NOTE: This key pair will never been shown again
7) Add a redirect URI by clicking in "ADD URI" and type: https://www.docusign.com
8) Copy the "Integration Key code" and past in a notepad
9) Copy the "User Id code" and past in a notepad
10) At profile menu, copy the "Account#" and past in a notepad
11) Grant consent to use API by accessing the custon URL:
    https://account-d.docusign.com/oauth/auth?response_type=token&scope=signature%20impersonation&client_id=<INTEGRATION KEY>&redirect_uri=https://www.docusign.com
    NOTE: Change the <INTEGRATION KEY> to you integration key
