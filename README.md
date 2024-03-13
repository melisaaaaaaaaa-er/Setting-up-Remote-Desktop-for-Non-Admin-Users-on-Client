# Setting-up Remote Desktop for Non-Admin Users on Client

![39](https://github.com/melisa-er/Setting-up-Remote-Desktop-for-Non-Admin-Users-on-Client/assets/157723219/1b885e80-56f5-461f-81a6-897136a3413b)

Login to Client-1 using the jane-admin account.

Go to System → Remote Desktop → “Select users that can remotely access this PC” → Add → input “Domain Users” → Check Names → OK

![40](https://github.com/melisa-er/Setting-up-Remote-Desktop-for-Non-Admin-Users-on-Client/assets/157723219/f36a09d2-62c3-45c6-8bcc-8f43d57bf3b2)

Now non-admin user accounts can login on Client-1.

On a network with hundreds if not thousands of clients, this process would be done through Group Policy. 
