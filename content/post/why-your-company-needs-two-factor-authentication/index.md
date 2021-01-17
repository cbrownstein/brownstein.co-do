+++
title = "Why Your Company Needs to Implement Two-Factor Authentication"
date = "2021-01-10"
description = """Read this article to learn what 2FA is and why you need it \
  to protect your company's data from hackers and cybercriminals."""
tags = [
  "cloud",
  "software",
  "business",
  "technology",
  "cybersecurity"
]
canonicalURL = "https://mdsitservices.com/2021/01/why-your-company-needs-to-implement-two-factor-authentication/"
client = "MDS IT Services"

[cover]
image = "YubiKey-4-keychain-and-YubiKey-4-Nano.png"
alt = "Picture of a YubiKey 4 on a keychain and a YubiKey 4 Nano"
caption = "Yubico, CC BY-SA 4.0 <https://creativecommons.org/licenses/by-sa/4.0>, via Wikimedia Commons"
relative = true
+++

Hackers and cybercriminals can easily take over your company’s valuable data
if you’re not using two-factor authentication (2FA).

Continue reading to learn more about 2FA and how MDS IT Services can help
implement it for your company.

## What is Two-Factor Authentication?

Two-factor authentication, also known as 2FA or multi-factor authentication,
is a security feature that, when enabled, requires more than a password to be
entered to access online accounts.

You might have already encountered forms of 2FA. For example:

- After trying to log into one of your online accounts, you are sent a code
  through SMS text message that you need to enter.
- After trying to log into one of your online accounts, you are sent an email
  containing a link that you need to click.

## What’s wrong with simply requiring strong passwords?

While it remains a good cybersecurity policy to require that members of your
company use strong passwords (passwords longer than 8 characters and
containing a combination of letters, numbers, and symbols), strong passwords
offer no protection if an attacker already has an account password.

Here is an example of how an attacker can gain possession of a password:

Early in 2020, MDS IT Services had to respond to an emergency call from one of
its law firm clients when an employee’s email account was taken over.

(For illustrative purposes, we’ll call the employee, “Alice.”)

Even though Alice had a strong, unique password, it didn’t protect her in this
case. Alice had unknowingly, but voluntarily, gave up her password to the
attacker.

(We’ll call the attacker, “Mallory.”)

Mallory had already taken over an email account belonging to an outside
attorney that Alice trusts.

(We’ll call the outside attorney, “Carol.”)

From outside attorney Carol’s email account, attacker Mallory sent an email to
law firm employee Alice, saying:

> Hi Alice,
> 
> I need you to review some documents ASAP.
> 
> Here’s a link to the documents.

The link took Alice to a fake page that looked identical to the real page that
Alice visits to log into her firm’s email service. The fake page was
controlled by Mallory.

Not knowing the page is fake, Alice unknowingly, but voluntarily, entered and
gave her login credentials to Mallory.

Because the law firm Alice works for wasn’t using 2FA, Mallory was able to
access years and years of Alice’s confidential emails.

The above is an example of a common attack used by cybercriminals, known as
“spear phishing.”

## How does 2FA improve security?

When 2FA is enabled, an attacker needs more than just your password to gain
access to your online accounts and sensitive data.

If the law firm in the above example had implemented 2FA, having the
employee’s password wouldn’t have been enough for the attacker to gain access
to the employee’s email.

One recommended implementation of 2FA is time-based one-time passwords, also
known as TOTP. With TOTP, users have an app, usually installed on their phone,
that generates a new code every 10 seconds or so. In order to log into an
online service, the code has to be entered along with the account password.
The code is valid only until a new code is generated, which is about 10
seconds.

If an attacker has only the account password and not the app-generated TOTP
code, the attacker will not be able to log into the account.

Currently, the best implementation of 2FA is the use of hardware tokens.

When hardware token 2FA is enabled, in order to log into an online service,
the user must plug a physical (hardware) device, e.g., a YubiKey, into their
computer, in addition to entering the proper account password.

Even if an attacker has the account password, if they don’t also have the
hardware token for the account, they will not be able to log into the account.

Hardware token 2FA is superior to TOTP 2FA because a single hardware token can
be used for many services, such as Gmail and Dropbox. With TOTP 2FA, unique
codes are generated for each individual service.

## How MDS IT Services help implement 2FA to secure your company’s data

The professionals at MDS IT Services have years of experience implementing 2FA
for companies and organizations of all sizes and across all industries.

Our engineers will make sure your company’s critical services, such as email
accounts and web servers, are protected from hackers, even if your passwords
are compromised.

Additionally, we will train the members of your company how to properly use
2FA to keep their accounts secure.

To learn more about how MDS IT services can help implement 2FA to secure your
company’s data, contact us to schedule a free consultation.
