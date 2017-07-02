# SecureParsedown [![Build Status](https://travis-ci.org/aidantwoods/SecureParsedown.svg?branch=master)](https://travis-ci.org/aidantwoods/SecureParsedown)

Parsedown, with added XSS protections.

Enable these with

```php
<?php

use Aidantwoods\SecureParsedown\SecureParsedown;

$Parsedown = new SecureParsedown;
$Parsedown->setSafeMode(true);
```

More info about this can be found at https://github.com/erusev/parsedown/pull/495

---

SecureParsedown is an extension to Parsedown. Parsedown was created by
Emanuil Rusev, and is available from https://github.com/erusev/parsedown.

---

## Reporting Security Issues

If you're reporting a security issue, you can still use the issue tracker, but
it would be great if you'd encrypt the issue for me before posting it
(please post in ascii armored format). And give the issue a generic title like
"Security Issue".

My GPG fingerprint is `A0EAF427E34F44505F171FB09A6A8EFAA512BBB9`, you can obtain
my key with:

```bash
gpg --recv-keys A0EAF427E34F44505F171FB09A6A8EFAA512BBB9
```

Additionally, you can verify that I, Aidan Woods am the owner of the
@aidantwoods GitHub account, the given GPG key, and various other online
identities via the signature chain available at https://keybase.io/aidanwoods/sigchain#6fc6b2061420868891261c72f7094e841fadfb37a577dd83ec5a6147138a9da80f.
I have also signed this commit.

It would be great if you'd also include your own GPG fingerprint in the message,
so I can reply to you in an encrypted format if neccesary.

How to encrypt:

Set up GPG, prepare your message in e.g. a file `msg.txt`

Run

```bash
cat msg.txt | gpg -sear A0EAF427E34F44505F171FB09A6A8EFAA512BBB9
```

Then copy and paste the output from the console into a new GitHub issue.

I shall try to convert issues to plain-text in-place when they are resolved, for the benefit of visibility.

## Other Issues
All other issues, please post in plain-text.