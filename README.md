# seceep
Password and Secrets management server built for individuals and small to medium size businesses

# About Seceep
Seceep is a Free and Open Source passwords and secrets management server built in c++ made to be interfaced by the API avaliable. This allows for others to create frontends that use gRPC to interface with Seceep. Seceep allows for a user or organization to create teams and have very granular control over permissions.

# Features
- LDAP
- MFA
  - Authenticator apps (google authenticator, microsoft authenticator, etc.)
  - Hardware keys (Yubikey, CryptoTrust, Kensington, etc.)
  - Bio authentication
- Strong Random Password generation
- Teams/groups

# Technologies
- gRPC to execute commands on the server
- PostgreSQL to store user data and passwords/secrets
