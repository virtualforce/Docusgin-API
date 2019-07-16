# Docusign API integration
  	The world’s leading platform for digital agreements
# Two way to digitial Signature
* REQUEST ESIGNATURE VIA EMAIL
* REQUEST ESIGNATURE IN YOUR APP

We will be exploring > Request esignature in your app


# REQUEST ESIGNATURE IN YOUR APP

Docusign provide different way of generating token to authenticate Docusgin account
*  OAuth Token Generator tool for demo purpose
*  Authorization code Grant
* Implicit Grant
* JWt Grant
# Difference between different type of authentication
Authorization Code Grant and Implicit Grant both are used when Our app demand individual authentication of the client
JWT authentication is used when we don't want client/signer to login to docusign app instead our app will impersonate on the behalf of Signer.

# How we get Docusgin signature

Admin will create and upload document to docusign. Docusign provide tools and autoplace anchor tags to put these placeholder on the documents called envelop. After finalizing envelop. our app will get envelop id that will be used to generate url for signer/client view where he will sign. 

We have 
* Embedded Signing view
* Embedded Sender view

we will be exploring more about these in future with examples

