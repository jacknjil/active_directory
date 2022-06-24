# 01- Install Domain Controller

1. Use 'sconfig' to:
    - change the hostname 
    - change IP address to static
    - change DNS server to our IP address

2. Install the Active Directory Windows Feature

'''shell 
Install-WindowsFeature -AD-Domain-Service -IncludeMangamentTools
'''