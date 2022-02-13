Authentication
•	Process which confirms user’s identity
•	They are who they say they are
•	Usually before grating access or allowing privileged actions
•	E.g. anyone processing key to a room can access it, you have the key, you are an authorized user
•	Necessary for access control, eg admin pages, paid content
Authentication Factors
•	Knowledge Based: Something the user KNOWS
Password, PIN, Mother’s maiden name
•	Ownership: Something the user HAS
Key, ID Batch, Ticket, Credit Card
•	Inherence: Something the user IS
Fingerprints, voice, face recognition

Legal system uses Signature which is combination of knowledge and inherence

o	Do not have to be unique
o	Something only the user knows
o	A password or a key can be shared by a group
o	Stronger authentication when they are unique
Credentials
•	Usually means username and password
•	Users have many online accounts
•	Need credentials to be secure but not a burden to use
•	Password managers
•	Avoid putting background images on username and password fields
•	Do not prevent the user or JavaScript from pasting values into username and password fields
•	Use HTTPS for secure communication: That will ensure that when the usernames and passwords are communicated from the user to the server, it's done securely through an encrypted channel, and can't be observed by anyone watching that traffic
Usernames
•	Username should be unique to your website
•	Username can be different from other websites, but does not need to be
•	In most cases, email address is a suitable username
Passwords
•	Form input of type “password”: Replaces input during text entry with dots
•	Shoulder surfing is the term used when someone’s sees your password while you are typing
•	

Password Requirements
•	Requires a minimum of 10 characters
•	Allow at least 64 characters
•	Allow and encourage character variety
•	Report password strength
•	Check for weak passwords
Enumeration
•	Testing usernames by trial and error to determine which usernames are valid
•	May reveal participation and violate a user’s privacy
•	Allows searching for passwords with that username
•	Prevent account enumeration attacks
Bad: “Username not found” and “Password is incorrect”
Good: “Username and password are incorrect”
Multi-Factor Authentication
•	Uses factors from more than one category
•	More secure than single-factor authentication
•	Hacker must have more than a password
•	Not multiple factors from same category
•	Example: ATM, user has ATM card and knows PIN number 
Online MFA
•	User creates an account with username and password
•	Site helps user set up and confirm an additional factor
o	SMS text message: HAS the mobile phone
	SMS includes passcode to enter
	SMS requires an SMS response
Popular services to integrate sending SMS from code: Twilio, Nexmo, TeleSign
o	Software authenticator
	Requests code from software authenticator
	Authenticator uses algorithm to generate a code
	Seed data on the device makes sure code is unique
	Authenticator changes codes every few minutes
	Knows password; has device capable of creating a valid, recent code
Google Authenticator, Microsoft Authenticator, LastPass Authenticator, Authy
o	Hardware authenticator
	Requests code from hardware authenticator
	User inserts hardware device into computer (USB)
	Device transmits a unique code
	Knows password; has hardware
YubiKey, Google Titan, Thetis 

twofactorauth.org lockdownyourlogin.com
One great resource for finding all of the websites that implement some form of multi-factor authentication is twofactorauth.org. You can go there and you can find out whether the different services that you're using online implement multi-factor authentication so that you can use it for yourself. And another good resource that you and your users can use is a website called lockdownyourlogin.com, which helps users to implement multi-factor authentication for themselves.

MFA Implementation Pitfalls
•	Most users are not familiar
•	Reluctance to provide additional data, example phone number
•	Unclear set-up instructions
•	Reliability, SMS facility not working, lost keyring with hardware authenticator
•	Error Handling
•	Customer Service Issues
Biometric Authentication
•	Inherence: Something the user is
•	iPhone Touch ID made it mainstream
•	Biometric Factors
o	Fingerprints
o	Retina/ Iris Scan
o	Facial Recognition
o	Voice matching
o	Vein matching – Palm print
o	DNA
o	Body geometry
o	Gait Analysis- How a person walk
o	Cranial resonance – the way that sounds vibrate inside someone’s head
•	Very difficult to forge
•	Very difficult to change, in case of data leak
•	

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
