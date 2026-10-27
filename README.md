# linux-hardening
Host router
    HostName 10.10.10.1
    User admin
    IdentityFile ~/.ssh/id_ed25519

Host lan-b
    HostName 10.10.10.20
    User marten
    ProxyJump router
    IdentityFile ~/.ssh/id_ed25519

    
