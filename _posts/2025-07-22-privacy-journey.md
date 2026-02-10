---
layout: post
thumbnail_image: /assets/posts/privacy-journey/hacker-hoodie.webp
title: "A Practical Guide to Overhauling Your Privacy"
description: A high-level overview of how I updated my personal privacy posture.
categories: Security
---

After nearly a year of silence, I'm happy to make my return to writing! A
lot has happened in the world since the days of yore (i.e. 2024). Whether it be
continued developments in the LLM arms race or even just greater clarity on the
release date of [Hollow Knight: Silksong](https://en.wikipedia.org/wiki/Hollow_Knight%3A_Silksong),
there's a lot to talk about. First, let's talk about privacy.

# Introduction

Information is more accessible now than it's ever been before, and 
unfortunately the burden of data privacy often falls upon the consumer. While
many products are expected to comply with national laws and regulations catered
towards protecting individual privacy, relying on third parties to protect your
data will leave numerous gaps in your privacy posture.

That being said, approaching your privacy can feel pretty daunting. Everyone
starts out in a different place, and a lot of resources either give too little
information or overload you on options. This post relays the process I took in
reconsidering my privacy posture, as well as some resources I stumbled upon
across the way. By the end, I hope you too can feel empowered to introduce one
new process or technology to help you improve your privacy.

# Why Should I Care About My Privacy?

Everyone's risk tolerance is different when it comes to privacy. Someone who is
casually using the internet to keep up with family and scroll through
short-form content has far fewer stakes than a political journalist in a 
country with an oppressive government. On a practical level, the amount of
effort that *should* be invested in protecting one's data varies. 

## Risk Categories

<figure>
  <img src="/assets/posts/privacy-journey/privacy-risk-levels.jpg" alt="Risk level graph" style="width: 100%;">
  <figcaption><em>A very high-level depiction of realized risk levels.</em></figcaption>
</figure>

For many individuals, there isn't an obvious reason why they should 
consider the kind of 
[governance, risk, and compliance (GRC)](https://secureframe.com/hub/grc/what-is-grc) 
standards that companies and governments are expected to follow. In my opinion,
everyone could benefit from incorporating some privacy best practices into 
their lives. To help demonstrate this point, let's discuss some broad 
categories of technology users:

- **Non-technical users**. For more casual technology users, a lot of simpler
steps towards improving privacy are also good first steps in improving security
(more [discussion on this below](#privacy-vs-security)).
Anyone who is high-profile, or might otherwise be concerned about other people
having easy access to private information, can take some simple steps to
improve the privacy of their data. This is especially prudent in an era where
personal information is easier to use and more in demand than ever before.

- **Tech lovers**. Anyone who is already literate with technology, whether it
be from working at a tech company or hobbyist appreciation, might enjoy
learning about the different privacy-focused technologies and practices that
exist. It's also possible that your work may require you to learn these
standards at some point, so there is some practical benefit as well. Where data
exists, privacy best practices do as well, so there's a lot of educational 
value in doing a privacy deep dive.

- **High-risk actors**. The value proposition of improving one's privacy tends
to be self-evident for anyone who is politically active or working directly 
with sensitive data. Examples of such folks may include activists, 
whistleblowers, and government employees. The risk of having one's identity or
data being revealed could quite literally impact the lives of many people.

## Privacy vs. Security

For those who are unfamiliar, privacy and security are *similar* but 
technically different concepts. In the context of this post:

- **Privacy**. Deciding who has access to your data.

- **Security**. Enforcing privacy decisions.

Here are some examples of situations with varying levels of privacy and 
security:

|                       | **Secure**                                       | **Not Secure**                                   |
|-----------------------|--------------------------------------------------|--------------------------------------------------|
| **Private**           | Having a quiet conversation at home. | Leaving a book with all your passwords on your desk at home. |
| **Not Private**       | Looking at your mobile bank account information on the bus.  | Reading aloud your credit card number in public. |

# Evaluating Your Risk Profile

Hopefully by this point you feel convinced of taking even one extra step in
your privacy enhancing journey. One open question that should be addressed,
before going into more technical detail, is how to decide what steps are worth
the effort.

A rough way to gauge the effort you want to put in is
by identifying yourself with one of the above risk categories. If you see
yourself handling "riskier" data, then you may want to take some extra steps.
Most people don't fall under this category, but nevertheless could see some
benefits (and get some peace of mind) by making some of the recommended changes
below.

In general, though, the bottom line is:

> Privacy isn't all or nothing; what you put in, you get out.

## Privacy Threat Modeling

In cybersecurity, [threat modeling](https://owasp.org/www-community/Threat_Modeling)
is a technique that gives security professionals a structured way of evaluating
the vulnerabilities of a system. There are a few different frameworks that are
typically followed to do this. Some of the most well-known models include
[STRIDE](https://en.wikipedia.org/wiki/STRIDE_model) and 
[PASTA](https://threat-modeling.com/pasta-threat-modeling/).

For privacy conscious folks who want a similar kind of framework, there exists a
privacy-specific analogue: [LINDDUN](https://linddun.org/threat-types/). In
summary (taken directly from LINDDUN's site):

- **L**inking. Associating data items or user actions to learn more about an
  individual or group.

- **I**dentifying. Learning the identity of an individual, through leaks, 
  deduction, or inference.

- **N**on-repudiation. Being able to attribute a claim to an individual.

- **D**etecting. Deducing the involvement of an individual through observation.

- **D**ata disclosure. Excessively collecting, storing, processing or sharing 
  personal data.

- **U**nawareness/unintervenability. Insufficiently informing, involving or
  empowering individuals in the processing of their personal data.

- **N**on-compliance. Deviating from security and data management best
  practices, standards and legislation.

Whenever you are interacting with software that stores sensitive data, you can
apply the principles of LINDDUN to determine how impacted your privacy posture
will be.

# Getting Started

Time to go through a ton of ways you can update your privacy! I've structured
the sections below as interactive checklists that you can step through at your
own pace. Before we dive in, though, I want to share the holy grails of privacy
guides: [Privacy Guides](https://www.privacyguides.org/en/) and 
[Privacy Tools](https://www.privacytools.io/).

> You are being watched. Private and state-sponsored organizations are 
> monitoring and recording your online activities. PrivacyTools.io provides
> services, tools and privacy guides to counter global mass surveillance. 
> Established in 2015 after Edward Snowden's revelations, and is now the most
> popular privacy website.

Much of this guide was inspired from the content on Privacy Tools. I highly
recommend checking out this site, and Privacy Guides, for additional 
information about privacy tooling.

I also recently discovered [Digital Defense](https://digital-defense.io/).
While I haven't yet had the chance to explore their lists in more detail, they
seem to be more comprehensive than what's detailed in this post (and have some
pretty helpful markers for actions that are essential, optional, and advanced).
If you finish reading this post and want more resources to check out, I would
recommend giving Digital Defense a try.

<figure>
  <img src="/assets/posts/privacy-journey/happy-cat.gif" alt="Happy jumping cat" style="width: 30%;">
  <figcaption><em>Me when I'm about to make my digital privacy better.</em></figcaption>
</figure>

# Privacy Checklists

## Pre-Overhaul

- [ ] Explore tool recommendations from [Privacy Tools](https://www.privacytools.io/)
    - A lot of alternatives are also listed below, but prefer options listed on Privacy Tools
- [ ] Install secure password manager (e.g. [NordPass](https://nordpass.com/), 
    [Bitwarden](https://bitwarden.com/), etc.)
    - tl;dr remember one password, decouple (and improve) the security of your remaining passwords
    - [Why You Should Use a Password Manager, and How to Get Started](https://www.howtogeek.com/141500/why-you-should-use-a-password-manager-and-how-to-get-started/)
- [ ] Set up email aliasing (e.g. [SimpleLogin](https://simplelogin.io/), [AnonAddy](https://addy.io/))
    - Equivalent to doing `name+alias@gmail.com`, except scalable across any service
    - Separating domains allows for greater control and observability into how sites use your data
- [ ] Switch to a privacy-respecting DNS (e.g. [NextDNS](https://nextdns.io/), 
    [ControlD](https://controld.com/), [Mullvad DNS](https://mullvad.net/en/help/dns-over-https-and-dns-over-tls))
    - Quite a bit of information is revealed by DNS; even if traffic is encrypted,
      a lot can be assumed by knowing where it goes
    - Another option is setting up a [Pi-hole](https://pi-hole.net/) (covers your whole network)
- [ ] Harden browser (e.g. [Librewolf](https://librewolf.net/), Hardened [Firefox](https://www.firefox.com/en-US/), 
    [Tor](https://www.torproject.org/))
    - FYI Firefox did 
      [recently have some backlash](https://thehackernews.com/2025/03/mozilla-updates-firefox-terms-again.html) 
      around its data handling
    - Personally I've found some sites struggle with hardened browsers (like
      streaming services), but they do bundle a lot of nice secure defaults
- [ ] Replace Google Search with [DuckDuckGo](https://duckduckgo.com/), 
    [Brave Search](https://search.brave.com/), or [SearXNG](https://searx.bndkt.io/)
- [ ] Try encrypted messengers (e.g. [Signal](https://signal.org), [Session](https://getsession.org/), 
    or [Matrix](https://matrix.org/))
    - It's hard to force everyone over to a secure messaging app, but a hybrid
      approach works well (having a handful of different apps and using them
      when you find other users)
- [ ] Evaluate encrypted cloud storage (e.g. [Proton Drive](https://proton.me/drive), 
    [Tresorit](https://web.tresorit.com/login))
- [ ] Install encrypted notes or task managers (e.g. [Standard Notes](https://standardnotes.com/), 
    [Joplin](https://joplinapp.org/))
    - Functionally this is nice since there is a great deal of cross-platform syncing
- [ ] Consider a private analytics/self-hosting tool (e.g. 
    [Umami](https://umami.is/), [Plausible](https://plausible.io/))
    - This is really only relevant if you run your own website

## Password & Account Security

- [ ] Choose a password manager
    - Create a good organization system with well-named folders
    - Consolidate information into one password manager (reduces attack surface)
    - Pair this with a good [authenticator app](https://www.pcmag.com/picks/the-best-authenticator-apps#)
        - There's [good discourse](https://www.reddit.com/r/PrivacyGuides/comments/xnqhqy/totp_codes_in_password_manager/)
          on using your password manager as an authenticator; evaluate the pros
          and cons to determine what will work best for you
    - Use passwordless options when possible (SSO via another identity provider, passkeys, etc.)
        - I recommend using physical MFA like [YubiKeys](https://www.yubico.com/)
          when possible; always register two different keys: a primary that you
          use and a backup that you leave in a secure location
    - (Recommended) Use aliased emails as usernames when required
- [ ] Migrate online accounts to chosen password manager
    - Delete unused accounts as you come across them
        - Can be [surprisingly difficult](https://backgroundchecks.org/justdeleteme/)
    - Rotate usernames (or use aliased emails) and passwords as you migrate
      services
        - Like deletion, you'll find some services make this hard or outright
          impossible
        - You can invoke regulations like GDPR as needed to make this easier
    - If possible, and you deem it worth the effort, add MFA to the account
- [ ] If your password manager has such capabilities built-in, consider running
    through various password quality reports (e.g. exposed, weak, reused, etc.
    passwords)

## Sensitive Data Audit

- [ ] Migrate notes to a privacy-first platform
    - [ ] Select encrypted notes tool
        - If you have text-based content distributed across many platforms (Google
          Keep, Apple Notes, etc.), move them all to a single location
        - You can also include digital journals in this category
    - [ ] Remove notes from old provider(s)
        - MAKE SURE your data is migrated and backed up before doing this
- [ ] Migrate photos to an encrypted location
    - [ ] Select private digital photo storage
        - Check out [Privacy Tools](https://www.privacytools.io/encrypted-photo-storage) for options
        - Proton Drive also recently added [secure photo storage](https://proton.me/drive/photo-storage)
    - [ ] Remove photos from old provider(s)
        - MAKE SURE your data is migrated and backed up before doing this
- [ ] Use privacy-focused cloud storage when possible
    - This may not always be possible, e.g. when collaborating on a Google Doc
    - Many solutions also have desktop apps that expose drives as shared
      folders, making use low friction and intuitive
- [ ] Delete or anonymize social media accounts
    - Social engineering is one of the most practical methods by which any
      person or company may actually become compromised; this method is
      enhanced by information that is easy to uncover in social media
    - On the other side of things, social media platforms provide a direct
      avenue of surveillance by both tech giants and third-parties
    - Removing social media entirely may be impractical, but using 
      [privacy frontends](https://www.privacytools.io/privacy-frontends) or
      using privacy controls native to social media apps is recommended
- [ ] Practice good email hygiene
    - In addition to using the email providers above, having a personal 
      retention policy on both received and sent emails is a good idea
    - Sensitive information lives in emails, so if it doesn't need to be kept
      long-term then archiving or deleting stale emails can help reduce your
      sensitive data footprint
- [ ] Evaluate sensitive document digital storage
    - Follow the [3-2-1 backup rule](https://www.veeam.com/blog/321-backup-rule.html)
    - Use vetted storage providers when choosing to backup digital data 

## Anonymization & Data Scrubbing

- [ ] Unsubscribe from snail mail
    - [ ] [Catalog Choice](https://www.catalogchoice.org/)
    - [ ] [Do Not Call Registry](https://www.donotcall.gov/)
    - [ ] [DMA Choice](https://www.dmachoice.org/)
    - [ ] [OptOutPrescreen](https://www.optoutprescreen.com/)
- [ ] Remove online public data
    - Follow high-level guidance on the [Data Removal Services](https://www.privacyguides.org/en/data-broker-removals/)
      Privacy Guide 
    - Try searching for your full name, usernames, and emails to get an idea of
      your full digital footprint
        - Consider brokers like Spokeo, Whitepages, etc.
        - You may need to request removal of data from data brokers manually
        - Unfortunately, there's no guarantee your data will be permanently
          removed (also, there are a *lot* of data brokers)
- [ ] (Optional) Consider using a data anonymization tool (e.g. 
    [Incogni](https://incogni.com/), [redact.dev](https://redact.dev/), etc.)
    - Plenty of these services have good reputations, though I would take a 
      look at both positive and negative reviews before moving forward with one
      of these tools

## (Optional) Deep Clean & Beyond

- [ ] Review and clean up browser extensions/add-ons
    - In general, you should be pretty selective in what browser extensions you
      use; by using an extension, you are trusting arbitrary code to be run
- [ ] Switch to a privacy-respecting mobile OS (e.g. GrapheneOS, CalyxOS)
    - This is really only valid if you use an Android device and, in general,
      are willing to put up with potentially unexpected software behavior
- [ ] Consider switching to open-source alternatives for:
    - [ ] Calendar (e.g. [Etar](https://github.com/Etar-Group/Etar-Calendar), 
      [Proton Calendar](https://calendar.proton.me/))
    - [ ] Contacts (e.g. [Nextcloud Contacts](https://docs.nextcloud.com/server/19/user_manual/pim/contacts.html))
    - [ ] Maps (e.g. [Organic Maps](https://organicmaps.app/), [Magic Earth](https://www.magicearth.com/))
    - [ ] Weather apps (e.g. [Forecastie](https://github.com/martykan/forecastie))
- [ ] If you use an iPhone, take advantage of 
    [iCloud Private Relay](https://support.apple.com/en-us/102602)
- [ ] Create burner accounts for niche services
    - Definitely abetted by using an email aliasing service
- [ ] Regularize future privacy habits e.g. annual privacy sweeps/audit reminders

# Final Thoughts

Thank you for joining me to the end of this post! I hope you learned something
new, took even just one step to improve your privacy, or at least enjoyed the
ride. This set of checklists is by no means comprehensive and is definitely 
opinionated. That being said, privacy is an ever-evolving field with new 
solutions being created every day. It never hurts to periodically pause, take
a look at your online data hygiene, and see if there's something new you can do
or a new tool to try out.

And remember:

<figure>
  <img src="/assets/posts/privacy-journey/big-brother.jpeg" alt="Big Brother is watching you" style="width: 100%;">
</figure>
