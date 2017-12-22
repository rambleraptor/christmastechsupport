---
layout: page
title: Make sure your passwords are different
time: 1 hour
---
Let's say you use the same password on every single website. Let's be real - it's most of us. >80% of people[^password-study] use the same password on every website. Maybe you have a super secure 30 digit password with lots of capitals, numbers, and symbols. Nobody could ever guess it (including maybe you...) Perhaps you're one of the 11% of people who have one of the following PINs[^datagenics]

|Rank|PIN|Frequency|
|---|---|---|
|#1|  1234|  10.713%|
|#2|  1111|  6.016%|
|#3|  0000|  1.881%|
|#4|  1212|  1.197%|
|#5|  7777|  0.745%|
|#6|  1004|  0.616%|
|#7|  2000|  0.613%|
|#8|  4444|  0.526%|
|#9|  2222|  0.516%|
|#10| 6969|  0.512%|
|#11| 9999|  0.451%|
|#12| 3333|  0.419%|
|#13| 5555|  0.395%|
|#14| 6666|  0.391%|
|#15| 1122|  0.366%|
|#16| 1313|  0.304%|
|#17| 8888|  0.303%|
|#18| 4321|  0.293%|
|#19| 2001|  0.290%|
|#20| 1010|  0.285%|

Nobody has to guess your password. Odds are that some website you use has leaked their usernames and passwords as part of a data breach. You can check out [HaveIBeenPwned][hibp] to see how many websites have leaked out your usernames, passwords and the like. A hacker can grab your username and password from one of these many leaks and then just log into every website they can think of.

The best solution is to use a different, complicated password for every single website. This can be really hard. Luckily, password managers can make it easy. A password manager will securely store all of your passwords for you - one for every account. When it's time to log in, your password manager will input in the correct username and password for you automatically. It can make logging
into websites easier and more secure.  The two most popular are [LastPass][lastpass] and [1Password][1password], although there's a bunch more[^pm-warning].


## Setting Up
1. Download a password manager app onto a computer.
2. Setup an account using a unique password. I'd recommend paying the monthly fee for cloud syncing (if there is a fee). It makes using a password manager a bit easier, and if your computer goes down your passwords aren't lost into the void.
3. Come up with a list of every digital account that your relatives have. At the very least, this list should have the following:
   * Email account
   * Facebook
   * Twitter
   * LinkedIn
   * Checking account
   * Investment accounts
   * Cell phone
4. Now comes the ~~boring~~ fun part! You have to log into each one of these accounts, change the password to be randomly generated, and then add the username/password to the password manager. Be sure to try logging into the account afterwards. I'd recommend *temporarily* copying the new randomly generated passwords to a text file until you're positive that your password manager has the correct password. Or, for the more extravagant, write it down on paper and then toss it into a nearby fire to ensure nobody will ever see it again.

5. Install your password manager on tablets + phones. Do not turn on biometric recognition. Be sure to log in to the password manager once to verify everything is working properly.

## Warnings!
* Most password managers don't handle changing passwords that well. Expect to be accidentally locked out of an account because your password manager didn't capture the password properly.  If they want to change passwords, have them copy all generated passwords into a text file temporarily and manually verify that the password manager has it remembered.

* If you're close with your relatives, write down a copy of their master password and store it in a secure place offline. This way, if they lose their password, you can help them recover access to their password vaults.

* Do **not** store your 2FA backup keys in your password manager! It may seem tempting, but keep them separate. If your password manager supports multiple "Vaults" with different passwords, perhaps.

* Some websites will allow symbols in their passwords and others won't. Some websites limit password length to x characters, some don't. You should make sure your relatives know how to play around with the settings on the password generator

* Password managers can fill out your password field for you and that can be scary. Try creating a fake email account using the password manager and then try changing the password on that account using your password manager. Then try changing the password on the fake account using your password manager. This way, if something bad happens, you just lose access to your fake account.

* Some mobile apps will have a little icon to open a password manager and others will require manually copying + pasting passwords.


[^password-study]: https://keepersecurity.com/assets/pdf/Keeper-Mobile-Survey-Infographic.pdf
[^pm-manager]: There's a whole bunch of very, very bad password managers out there that can make you less secure. Be sure that you understand why your password manager is secure. Most password managers have security white-pages and you can Google around for basic primers on password manager security to know what to look for.
[^datagenics]: https://www.datagenetics.com/blog/september32012/

[hibp]: https://haveibeenpwned.com/
[lastpass]: http://www.lastpass.com/
[1password]: https://www.1password.com/
