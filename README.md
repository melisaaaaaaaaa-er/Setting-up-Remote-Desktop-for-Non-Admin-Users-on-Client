# Setting-up Remote Desktop for Non-Admin Users on Client

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/39.png"/>

Login to Client-1 using the jane-admin account.

Go to System → Remote Desktop → “Select users that can remotely access this PC” → Add → input “Domain Users” → Check Names → OK

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/ADDS-images/main/40.png"/>

Now non-admin user accounts can login on Client-1.

On a network with hundreds if not thousands of clients, this process would be done through Group Policy. 
