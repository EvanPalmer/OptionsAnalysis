## Problem
The client would like to secure their new application with MFA (2FA) and a new identity service
The client would like to secure their existing application with MFA (2FA).

## Requirements
* Send custom emails and SMS during sign up and password reset
* Can be easily integrated with AWS APIs
* Must authenticate with SMS
* Must authenticate with Email
* Must authenticate with Soft Token
* Must support session time out

## Assumptions
* May be an incremental upgrade to existing identity service, or a complete uplift with migration
* Should use the same soft token for both old and new app
* 


### Kony Identity Service
#### Pros
* 
#### Cons
* 
#### Summary



### Okta
https://www.okta.com/products/adaptive-multi-factor-authentication/ 
#### Pros
* Excellent Kony Integration
* Excellent Integration with AWS 
* Supports SMS
* Supports email
* Supports soft token
* Can support complete identity service replacement

#### Cons
* Does not integrate with existing Identity solution




### Authy/Twilio
https://authy.com/features/setup/ 
#### Pros
* Excellent language support
* Excellent SMS support (need to store number in Twilio)
* Supports soft token
* Supports integration with existing identity solution

#### Cons
* No specific Kony integration
* Can’t send email
* Does not support complete identity solution


### Auth0
Pros
* Excellent language support
* Supports SMS
* Supports Soft Token
* Integrates with existing Identity Solution
Cons
* Does not support email
* No out-of-the-box Kony support, but can be implemented


### AWS
Pros
* Already using AWS

#### Cons
* 



### Azure
#### Pros
* 
#### Cons
* Currently using AWS


### Sales Force
#### Pros
* 
#### Cons
* 




### GoogleAuthenticator
https://medium.com/@richb_/easy-two-factor-authentication-2fa-with-google-authenticator-php-108388a1ea23
#### Pros
* Very easy to implement
* Lots of language support
* Flexible enough to lock down only required application features
* Free
* Supports integration with existing identity system

#### Cons
* Very generic
* Does not send emails or SMS
* Does not support complete identity solution



### Other Options
RSA: https://www.rsa.com/en-us/products/rsa-securid-suite/rsa-securid-access/securid-software-tokens
Entrust: https://www.entrust.com/multi-factor-authentication-tools/
Teneo: https://www.teneo.net/au/technologies/by-solution/security/ 
Centrify
Symantic VIP
Gigya
Imprivata

