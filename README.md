# vault-notes
recipes about hashicorp vault. 


### Secret management problems
    
    Secret -> credentials that gives you authentication or auhtorizations:
        - usernames
        - db credentials
        - API tokens
        - TLS certs
  
    
    Secret sprawl :
        - source code
        - configuration management
        - vcs

    Who grant access
    Secret rotation


### Vault improves secret management: 
- Centralize secrets
- Encrypt secrets
- Fine grain access control throught ACL's
- Audit
- Dynamic secrets -> short live secrets | ephemeral
- Revocation
- Encrypt as service
- key management - lifecyle

### Vault components
- Core
  - lifecycle management
  - ensuring requets are processed
- Authentication Backends
  - Allow Vault to allow clients to authenticate from diferrent systems. 
- Auditing
  - Trails of who is doing what
- Storage Backends
  - Storing data at rest (it could be RDBM, Consul, etc)
- Secret Backends
  - key/value
  - Dynamic secrets
  - PKI
  - SSH

Vault Installation
- [brew](https://learn.hashicorp.com/tutorials/vault/getting-started-install?in=vault/getting-started)

    