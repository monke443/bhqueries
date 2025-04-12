A compilation of custom bloodhound legacy queries of redteaming and pentesting

# Easy Wins

    Find all active Domain Admin sessions
    Find all edges any owned user has on a computer
    Find if any domain user has interesting permissions against a GPO
    Find dangerous ACLs (User -> User/Group)
    Find dangerous ACLs (User -> Computer)

# High Value

    Find groups that can reset passwords
    Find groups that have local admin rights
    Find all users that have local admin rights
    Find groups that contain both users and computers
    View all groups that contain the word 'admin'
    Find if unprivileged users have rights to add members into groups
    Find MSQL
    Find all computers with unsupported operating systems

# Object Info

    View all GPOs
    Find all sessions a user in a specific domain has
    Find what groups can RDP
    Find machines Domain Users can RDP into
    Find all users that are part of the VPN group
    Find users that logged in within the last 90 days
    Find users that have never logged on and account is still active

# Kerberos Delegation

    Find all computers with Unconstrained Delegation
    Find computers that allow unconstrained delegation that AREN’T domain controllers
    Find constrained delegation
    Find groups that contain both users and computers
    Find computers with constrained delegation permissions and the corresponding targets where they are allowed to delegate

# Certificates

    Find all Certificate Templates
    Find enabled Certificate Templates
    Find Certificate Authorities
    Show Enrollment Rights for Certificate Template
    Show Rights for Certificate Authority

# ADCS ESC (Active Directory Certificate Services ESC)

    Find Misconfigured Certificate Templates (ESC1)
    Shortest Paths to Misconfigured Certificate Templates from Owned Principals (ESC1)
    Find Misconfigured Certificate Templates (ESC2)
    Shortest Paths to Misconfigured Certificate Templates from Owned Principals (ESC2)
    Find Enrollment Agent Templates (ESC3)
    Shortest Paths to Enrollment Agent Templates from Owned Principals (ESC3)
    Shortest Paths to Vulnerable Certificate Template Access Control (ESC4)
    Shortest Paths to Vulnerable Certificate Template Access Control from Owned Principals (ESC4)
    Find Certificate Authorities with User Specified SAN (ESC6)
    Shortest Paths to Vulnerable Certificate Authority Access Control (ESC7)
    Shortest Paths to Vulnerable Certificate Authority Access Control from Owned Principals (ESC7)
    Find Certificate Authorities with HTTP Web Enrollment (ESC8)
    Find Unsecured Certificate Templates (ESC9)
    Shortest Paths to Unsecured Certificate Templates from Owned Principals (ESC9)
  


    
