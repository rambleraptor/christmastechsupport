---
layout: page
title: Two Factor Authentication
time: 1 hour
---
A regular account only requires one factor to login. (a password). If somebody
had your password, they could log into your account.

Passwords can be stolen relatively easily. To combat this, many services
support two factor authentication.

Accounts with two factor authentication require two things to login: something
you know (a password) and something you have (your phone). It should be much
harder for a hacker to physically steal your phone from you.
## Long Explanation
Two factor (or multi-factor) authentication is the practice of receiving a code
from somewhere and entering it when trying to login. This can come in many
forms.

* SMS. A website will text you a code that must be entered online to login.
  This isn't ideal. It's very much a last resort. SMS is horribly insecure
  (see: SS7). Assume that anything you send over text could become public
  information. That being said, it's better than nothing! Use it as a last
  resort.

* Email. A website will email you a code that must be entered online to login.
  This is getting better. Still try to avoid this if at all possible.

* App. This is your best bet.. There's a lot of apps out there that support this
  kind of two factor authentication (Duo, Authy, Google Authenticator). You can
  use any of them - it doesn't matter. When you want to login to a site, you'll
  open the app and get a code. Using an app is much more secure than the past two options.

* Security Key. This is the best option, but it doesn't work well on mobile.
  You can buy a U2F key (kind of like a flash drive) that will automatically
  enter a code for you. When it's time, you insert your U2F key and it'll
  handle the rest. This is the most secure option because it doesn't rely on
  very much software. You don't have to worry about your app having a security
  flaw. That being said, very few sites support security keys.

## Setting Up
1. Come up with a list of every digital account that your relatives have. At
   the very least, this list should have the following:
   * Email account
   * Facebook
   * Twitter
   * LinkedIn
   * Checking account
   * Investment accounts
   * Cell phone
2. Download an app to use with your two-factor accounts. You can do some
   research, but they all act the same. If you want cloud backups, use Authy.
   (Some people will tell you that cloud backups defeat the purpose of 2FA.
   That's partially true. You assume more risk, but it's easier. Make the
   judgement call yourself).
3. Now comes the fun part! You'll have to enable 2FA on every account. This
   differs greatly on every site, so here's the instructions for many popular
   sites. Remember - you'll want to use App based 2FA if at all possible.
Google
Facebook
Twitter
LinkedIn
Chase

4. Everytime you get a QR Code, take a snapshot of it and save it in a special folder. These are your backups. If you need to add a new device, you'll need to reinput all of these QR codes into your new device. Store these QR codes in a very secure place. Printing them out and storing them in a vault would be ideal.

## Teaching
* Try logging into a 2FA account.

## Avoiding Problems
* You should have a way of backing up your second factor. If your relative
  loses their phone (or gets a new one!), they should be able to get all of
  their two factor accounts working on the new phone quickly. I recommend
  keeping a backup of all of the two factor seed values or using a
  second-factor app that supports backups (like Authy).
