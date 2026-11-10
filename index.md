# Lock Files — Privacy Policy

**Last updated: 10 November 2026**

## The short version

Lock Files cannot see your photos. Not "does not look", cannot. There is no
account, no server that holds your data, and no key anywhere but on your
device. If you forget your pattern and lose your recovery phrase, your photos
are gone — including to us. That is not a gap in this policy; it is the whole
design.

## What we collect

**Nothing.** There is no analytics code in this app, no advertising
identifier, no crash reporting, and no account to create. We do not know how
many photos you have, how often you open the app, or whether you use it at
all.

There is no crash reporting of any kind, not even as an option you could turn
on: the app contains no reporting or analytics library at all. The only
things that ever leave your device are a backup or a share you asked for, and
both are encrypted before they go.

### Failed unlock attempts

Lock Files can keep a list of times someone tried a wrong pattern or
passphrase. It is **off unless you turn it on**, it is encrypted on your
device, it is never uploaded, and it records only that an attempt happened and
when — never what was drawn or typed. Successful unlocks are never recorded:
a list of when you opened your own vault would be far more sensitive than a
list of when somebody failed to.

## What stays on your device

- Your photos, videos and files, encrypted.
- The index describing them (names, dates, folders), encrypted.
- Your keys, in the device Keychain, protected by the hardware.

Your pattern or passphrase is never stored anywhere. It is used to derive a
key and then discarded. Your recovery phrase is never stored either — which is
why the app cannot show it back to you, only issue a new one.

## What leaves your device, and only if you ask

### iCloud backup (optional)

If you turn on backup, encrypted records are copied to **your own iCloud
account**, in a private database. Three things follow from that:

- The storage is yours, not ours. It counts against your iCloud quota.
- **Apple cannot read it.** The records are encrypted on your device with a key
  derived from your pattern, which Apple never receives.
- **We cannot read it, or even see that it exists.** A private CloudKit
  database is not visible to app developers. There is no console we can open.

### Sharing a vault (optional)

If you create a share, an encrypted copy is published where the person you
share with can fetch it, and you are given nine words to send them. Anyone with
those words can open that copy. We cannot: the words never reach us and the
copy is ciphertext without them.

Revoking a share deletes the copy. Be clear about what that does and does not
do: it stops anyone opening it from then on. It cannot take back what someone
has already looked at or saved. **Sharing a vault is trusting a person.**

### Nothing else

There is no other network traffic. No telemetry, no "checking for updates" ping
carrying your identifiers, no remote configuration.

## Permissions, and why each one is asked for

| Permission | Why |
|---|---|
| Photos | To read the items you pick, so they can be encrypted into your vault. Only what you select. |
| Photos (add/modify) | Only if you choose to *move* photos in, which needs permission to remove them from your library. |
| Camera | To capture directly into the vault. Captures never touch your camera roll. |
| Microphone | To record sound while recording video into the vault. |
| Face ID / Touch ID | To unlock without drawing your pattern. The key is held by the Secure Enclave and never leaves it. |

Every one of these is optional. Declining any of them leaves the rest of the
app working.

## Children

Lock Files is not directed at children and collects no data from anyone,
including children.

## What happens if you delete the app

Everything goes with it: the encrypted files, the index, and the keys in the
Keychain. If you had backup turned on, the records in your own iCloud remain
until you delete them from your iCloud storage — we cannot delete them for you,
because we cannot reach them.

## Your rights, and the honest limits of them

Data protection law gives you rights to access, correct, export and erase the
personal data a company holds about you. We hold none. There is nothing for us
to show you, correct, export or delete, and no request you could make that we
could act on. Your data is in your hands, which is the point, and also means
the responsibility for keeping your recovery phrase safe is yours.

## Changes to this policy

If this policy changes, the updated version ships with the app update that
changes the behaviour, and the date at the top changes with it.

## Contact

- Email: malihazmn12@gmail.com
- Policy URL: https://maliha3.github.io/lockfiles-privacy/
