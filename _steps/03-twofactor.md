---
layout: page
title: Two Factor Authentication
time: 1 hour
---
Imagine somebody steals your bank password. It can sadly be easier than you'd
like. They could get it from a data breach or phish you (trick you into typing
it into a website that looks like your bank, but isn't). How could you stop
them from logging into your bank and taking your money?

Enter two-factor authentication (also called multi-factor, multi-step, etc,
etc). Accounts with two factor authentication require two things to login:
something you know (a password) and something you have (your phone). A hacker
would have to steal your cell phone from you and get your password to get into
your bank.

# Wait, so what's two-factor authentication?
Two-factor authentication is the practice of getting a one-time use code from
some physical thing you own (your phone). Every time you log in, you need a
different code. The only place to get this code from one your second-factor
(your phone), which is making up new codes every thirty seconds. This means
that a hacker would need to steal your phone or else he/she could never know
the code to log into your account.

## Types of Two Factor
There's a bunch of different ways you can use two-factor. You've hopefully done
one of these before.

* Text message. A website will text you a code that must be entered online to
  login.  This isn't ideal. It's very much a last resort. SMS isn't very
  secure That being said, *it's better than nothing!* Not very secure is way,
  way better than not secure at all. Use it as a last resort.

* Email. A website will email you a code that must be entered online to login.
  This is getting better. Still try to avoid this if at all possible.

* Mobile App. This is your best bet! It's convenient, widely supported, and
  pretty easy to setup. I'd recommend using either Authy ([Android][authy-android], [iOS][authy-ios]) or Google
  Authenticator([Android][googleauth-android], [iOS][googleauth-ios]). The biggest difference is that Authy will
  work on multiple devices at the same time and Google Authenticator won't.

* Security Key. This is the best option, but it doesn't work well on mobile.
  You can buy a U2F key (kind of like a flash drive) that will automatically
  enter a code for you. When it's time, you insert your U2F key and it'll
  handle the rest. This is the most secure option because it doesn't rely on
  very much software. You don't have to worry about your app having a security
  flaw. That being said, very few sites support security keys.

## Setting Up
1. Come up with a list of every online account that you have. At the very
   least, this list should have the following:
   * Email account
   * Facebook
   * Twitter
   * LinkedIn
   * Checking account
   * Investment accounts
   * Cell phone

     Need some ideas? Visit this [website][twofactorlist] for a
     great list of all the websites that support two-factor authentication.

2. Download an app to use with your two-factor accounts.
3. Now comes the fun part! You'll have to enable 2FA on every account. This
   differs greatly on every site, so here's the instructions for many popular
   sites. Remember - you'll want to use App based 2FA if at all possible. If
   you can't figure out how to turn on two-factor auth, just google 'website
   2fa'. You'll figure out pretty quickly if a website allows two-factor
   authentication

   * [Google][google]
   * [Facebook][facebook]
   * [Twitter][twitter]
   * [LinkedIn][linkedin]

4. Try logging into your account just to make sure everything's working.
   Remember - you'll need to have your phone charged and by your side.

## Warnings!
* If you're worried about setting this up, try making a fake Gmail account and
  setting up two-factor authentication on that. It's a great way to convince
  yourself that you won't accidentally lock yourself out of your accounts
  accidentally.

* You should have a way of backing up your second factor. If your relative
  loses their phone (or gets a new one!), they should be able to get all of
  their two factor accounts working on the new phone quickly. I recommend
  keeping a backup of all of the two factor seed values (those QR codes) or using a
  second-factor app that supports backups (like Authy).

[twofactorlist]: https://twofactorauth.org/
[authy-android]: https://play.google.com/store/apps/details?id=com.authy.authy
[authy-ios]: https://itunes.apple.com/us/app/authy/id494168017
[googleauth-android]: https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=en
[googleauth-ios]: https://itunes.apple.com/us/app/google-authenticator/id388497605?mt=8

[google]: https://www.google.com/landing/2step/index.html
[facebook]: https://www.facebook.com/help/148233965247823
[twitter]: https://help.twitter.com/en/managing-your-account/two-factor-authentication
[linkedin]: https://www.linkedin.com/help/linkedin/answer/544/turning-two-step-verification-on-and-off?lang=en
