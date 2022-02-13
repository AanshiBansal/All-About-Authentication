### What is Authentication ?
- Process which confirms user’s identity
- They are who they say they are
-	Usually before grating access or allowing privileged actions
-	E.g. anyone processing key to a room can access it, you have the key, you are an authorized user
-	Necessary for access control, eg admin pages, paid content
### Authentication Factors
1. **Knowledge Based**: Something the user **KNOWS**
  - Password, PIN, Mother’s maiden name
2. **Ownership**: Something the user **HAS**
  - Key, ID Batch, Ticket, Credit Card
3. **Inherence**: Something the user **IS**
  - Fingerprints, voice, face recognition

Legal system uses Signature which is combination of knowledge and inherence

### Characteristics of Password
- Do not have to be unique
- Something only the user knows
-	A password or a key can be shared by a group
-	Stronger authentication when they are unique

### Credentials
-	Usually means username and password
-	Users have many online accounts
-	Need credentials to be secure but not a burden to use
-	Password managers are efficient of managing passwords
-	Avoid putting background images on username and password fields
-	Do not prevent the user or JavaScript from pasting values into username and password fields
-	Use HTTPS for secure communication: That will ensure that when the usernames and passwords are communicated from the user to the server, it's done securely through an encrypted channel, and can't be observed by anyone watching that traffic

### Usernames
-	Username should be unique to your website
-	Username can be different from other websites, but does not need to be
-	In most cases, email address is a suitable username

### Passwords
-	Form input of type “password”: Replaces input during text entry with dots
-	Shoulder surfing is the term used when someone’s sees your password while you are typing

### Password Requirements
-	Requires a minimum of 10 characters
-	Allow at least 64 characters
-	Allow and encourage character variety
-	Report password strength
-	Check for weak passwords

### Enumeration
-	Testing usernames by trial and error to determine which usernames are valid
-	May reveal participation and violate a user’s privacy
-	Allows searching for passwords with that username
-	Prevent account enumeration attacks
  - Bad: “Username not found” and “Password is incorrect”
  - Good: “Username and password are incorrect”

### Multi-Factor Authentication
-	Uses factors from more than one category
-	More secure than single-factor authentication
-	Hacker must have more than a password
-	Not multiple factors from same category
-	Example: ATM, user has ATM card and knows PIN number 

### Online MFA
-	User creates an account with username and password
-	Site helps user set up and confirm an additional factor
  - SMS text message: HAS the mobile phone
  - SMS includes passcode to enter
  - SMS requires an SMS response
- Popular services to integrate sending SMS from code: Twilio, Nexmo, TeleSign
- Software authenticator
  - Requests code from software authenticator
  - Authenticator uses algorithm to generate a code
  - Seed data on the device makes sure code is unique
  - Authenticator changes codes every few minutes
  - Knows password; has device capable of creating a valid, recent code
  - Google Authenticator, Microsoft Authenticator, LastPass Authenticator, Authy
- Hardware authenticator
  - Requests code from hardware authenticator
  - User inserts hardware device into computer (USB)
  - Device transmits a unique code
  - Knows password; has hardware
  - YubiKey, Google Titan, Thetis 

### MFA Implementation Pitfalls
- Most users are not familiar
- Reluctance to provide additional data, example phone number
- Unclear set-up instructions
- Reliability, SMS facility not working, lost keyring with hardware authenticator
- Error Handling
- Customer Service Issues

### Biometric Authentication
- Inherence: Something the user is
- iPhone Touch ID made it mainstream
- Biometric Factors
  - Fingerprints
  - Retina/ Iris Scan
  - Facial Recognition
  - Voice matching
  - Vein matching – Palm print
  - DNA
  - Body geometry
  - Gait Analysis- How a person walk
  - Cranial resonance – the way that sounds vibrate inside someone’s head
- Very difficult to forge
- Very difficult to change, in case of data leak
