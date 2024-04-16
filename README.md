# DISCORD ACCOUNT GENERATOR

A program that creates unflagged discord accounts on mobile

```diff
- WARNING: THIS ONLY WORKS ON ANDROID DEVICES (I HAVEN'T TESTED IT ON ANY OTHER DEVICES SUCH AS ON DESKTOP COMPUTERS)
```

## Features

- Uses AI to bypass captcha (using Hugging Face API)
- Android Friendly
- No Phone Locked Accounts (make sure to use good VPNs like: [Phone Gaurdian VPN](https://play.google.com/store/apps/details?id=com.distimo.phoneguardian))
- 100% Free, no need to buy captcha solvers and proxies. Can work on a phone alone

## Disadvantages

- Slow (1-3 minute per account, that's 30-60 accounts per hour. Depends on your phone)
- Unmaintainable Code
- Uses Temporary Emails
- Not Phone Verified (couldn't find any free services that works)
- No Profile Pictures (to prevent account getting flagged)
- Might Get Patched Soon (make an issue if it's patched)

## Set up

- [Download and Install Termux](https://f-droid.org/en/packages/com.termux/) (for terminal)
- [Download and Install Termux:API](https://f-droid.org/en/packages/com.termux.api) (for controlling the browser, email verification)
- [Install Python inside Termux](https://wiki.termux.com/wiki/Python)
- install requirements (bash) `pip install -r requirements.txt`
- Get [Hugging Face API Token](https://huggingface.co/settings/tokens)
- Paste the Hugging Face Token in `main.py line 17`
- Get your invite link and paste it in `main.py line 18`
- Enter email alias in `main.py line 19` (alphanumeric only and dashes)
- set password for each account in `main.py line 20`
- Go to the project's location and run the file (bash) `python main.py`

## Suggestions

Discord App
- [Discord Version 126.21](https://www.apkmirror.com/apk/discord-inc/discord-chat-for-gamers/discord-chat-for-gamers-126-21-stable-release/) (fast, less buggy)
- [Aliucord](https://github.com/Aliucord/Aliucord#-installation) (like Discord 126.21 but with token login)

VPNs:
- [Phone Gaurdian VPN](https://play.google.com/store/apps/details?id=com.distimo.phoneguardian)
- [Planet VPN](https://play.google.com/store/apps/details?id=com.freevpnplanet)

Kaspersky, Turbo VPN, Secure VPN, Thunder VPN don't work for me

## Disclaimer

- This project is against [Discord's Term of Service](https://discord.com/terms) and could lead your accounts getting terminated if found.
- This project is a proof of concept only.
- I am not responsible for anything that may happen to your account (please be careful and don't be silly).
