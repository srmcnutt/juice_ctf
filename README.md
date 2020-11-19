# Juice Shop CTF set up instructions

Greetings programs!

Below are the instructions to get started with the Juice Shop CTF Setup.

**Before diving in, please note the following:**
1. email doesn't work.
2. save passwords and access codes
3. if you neglect to do the above just create a new account

**Juice shop Server:**
http://juice.abl.ninja
 
**CTF Server:**
http://ctf.abl.ninja:4000
 
 
## Basic team setup:
 
**Juice shop provisioning/Team creation**

Go to http://juice.abl.ninja
1. Create team
    Multi-juicer will spin up an instance of juice shop for you
2. Save the code!
    This allows other people to join your team
    It also allows you to rejoin your own team if your cookie is deleted*

*Juice balancer balancer gives your browser a cookie that routes you to your juice shop instance automagically on subsequent connetions*

** CTF server provisioning **
1. Go to http://ctf.abl.ninja:4000
2. Create an account
3. Save password!
    Email service not set up so there is no password reset
4, Create a team
5. Save your team password
    This allows teammates to join your team on the ctf server
6. View challenges
 
## Playing the game:
1. Pick a challenge to solve (always start with the scoreboard)
2.  Copy the reg code from the solved challenge
3.  Go to the challenges page on ctf.abl.ninja
4. Find the card for the challenge you solved
5. Input the reg code.  CTF Server will give you credit for the solved challenge
6. Don’t share reg keys with your competitors!  Haha
 
A team can be multiple people or just one person totally optional.

Contest Ends at midnight.

## Bonus
if you want to run your own juice shop instance instead of using a hosted one, simply paste the command below into your terminal (note: you must have docker installed)

docker run  -e 'CTF_KEY=zLp@.-6fMW6L-7R3b!9uR_K!NfkkTrX' -e 'NODE_ENV=ctf' -p 3000:3000 bkimminich/juice-shop

Then connect to http://localhost:3000
 
