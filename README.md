This App is currently in Development!

# What StormShop is ...

StormShop is a project that sells scripts and subscriptions (mostly for Russian users).
You can buy it on our [website](https://nitro-storm.ru) / [telegram bot](https://t.me/storm_nitro_shop_bot) / [discord server](https://discord.gg/BNsV86yGQA) ... etc.

What about scripts? You can easily buy them on our [website](https://nitro-storm.ru). After purchasing you get the archive and README.md file with all instructions. If you wish, we can add you into private GitHub repository with the script you purchased!

# How to Install

```
git clone https://tailormind-design-studio-admin@bitbucket.org/tailormind-design-studio/storm-shop.git

npm install

npm start
```

# Basic Technical Test

![Logo](public/landing.PNG)

1. Remove Subscripts and Scripts Buttons from header
2. Instead, add `Create Account` and `Login Account` buttons

In order to submit your test, create a github repository and push all your changes to this repository and share the repository link with your recruiter.

## Changes Made

### Header Component (`src/components/Header/Header.tsx`)

**Removed:**

- SUBSCRIPTIONS button (with DiamondRoundedIcon)
- SCRIPTS button (with CodeRoundedIcon)

**Added:**

- "Create Account" button (pink) with PersonAddRoundedIcon → links to `/signup`
- "Login Account" button (blue) with LoginRoundedIcon → links to `/login`

**Updated:**

- Burger menu items to match the new navigation
- Import statements to include new icons and remove unused ones

**Routes:**

- `/signup` - Registration page (existing)
- `/login` - Login page (existing)