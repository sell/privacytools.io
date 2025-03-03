# Contributing Guidelines

Please read this document in full before contributing.

- [Rules](#rules)
- [Quality over Quantity](#quality-over-quantity)
- [Software Criteria](#software-criteria)
  - [Main (All Software)](#main)
  - [Providers](#providers)
    - [DNS](#dns)
    - [VPN](#vpn)
    - [Email](#email)
  - [Hardware](#hardware)
  - [Software](#software)
  - [Encryption](#encryption)
  - [Operating Systems](#operating-systems)
- [Images](#images)
- [Licensing](#licensing)
- [Contributing via email](#contributing-via-email)

## Rules

- Be nice and respectful.
- English only.
- Be constructive.
- Please feel free to *review changes* in the *files changed* tab of any
  pull request at any time.
- See also our [Code of Conduct](https://github.com/privacytoolsIO/.github/blob/master/CODE_OF_CONDUCT.md)

## Quality over Quantity

We're trying to keep it simple and promote the best tools, not all of them.

## Software Criteria

### Main

- Easy to use. Could your mother use that tool or service? Usability is most important.
- Cross-platform / Accessible.
- Privacy respecting.
- Open Source / Free Software is preferred but not required.
- Prioritize Products without Vendor Lock-in (decentralized/self-hostable) or data interoperability.

There can be exceptions if no software is available that meet the criteria.

Note: This criteria applies to all of the PrivacyTools website and recommendations.

### Providers

- Prioritize Products by privacy respecting nationality.

### DNS

- Supports DoH or DoT (We love DNSCrypt, but there is already https://github.com/DNSCrypt/dnscrypt-resolvers which is directly supported by dnscrypt-proxy, so we don't consider useful to list providers only supporting it).
- Supports DNSSEC (https://dnssec.vs.uni-due.de/ can test your current DNS provider).
- Doesn't log IP addresses during normal operation (If your suggestion logs, please compare its privacy policy with other servers on our table that keep logs).
- Preferably supports QNAME minimization (if you have access to the dig command, `dig +short txt qnamemintest.internet.nl` or `Resolve-DnsName -Type TXT -Name qnamemintest.internet.nl` if you are on Windows 10)

### VPN

See https://www.privacytools.io/providers/vpn/#criteria for more details.

- Prioritize Products by privacy respecting nationality.
- Cannot be based in USA or UK.
- Must be accessible via Open Source Software (e.g. OpenVPN, WireGuard)
- Use Encryption
- Accept Cryptocurrency
- No logging policy

### Email

- Outside of USA
- Support SMTP SSL
- Accessible Using Open Source Software (e.g. allows IMAP)

### Hardware

- Must be [H-Node Class A](https://h-node.org/wiki/page/en/compatibility-classes) or equivalent (if applicable)
- Must prioritize hardware certifications like [RYF](https://ryf.fsf.org/), [OSHWA](https://certification.oshwa.org/), and OSI when available.
- Cannot lock users to a particular platform.

### Software

- Must be able to download over encrypted network (can be a mirror)
- Must be Open Source Software

### Encryption

- Only verifiable encryption is to be trusted

### Operating Systems

- Must state if recommends, depends on, or offers non-free software (contrib)
- No Tracking Policy (opt-in analytics is ok)

## Images

- Provider logos are 200px x 70px ([example](https://github.com/privacytoolsIO/privacytools.io/blob/master/assets/img/provider/Mullvad.png))
- Tool logos are 120px x 120px ([example](https://github.com/privacytoolsIO/privacytools.io/blob/master/assets/img/tools/Firefox.png))

## Licensing

The content and original technology of this website is made available under the Creative Commons Zero v1.0 Universal license text. Some files or folders may include works from other projects with separate licenses, and will be marked as such. **By contributing to this repository, contributors do not necessarily agree to sign a CLA or legally transfer their copyright to the project, but they do at a minimum agree to license their work under the current license of this repository: In this case, the Creative Commons Zero v1.0 Universal.**

## Contributing via email

If you have a GitHub account, or are able to create a GitHub account, we ask that you do not submit issues via email.

If you do not have a GitHub account, you may submit software recommendations or other issues via email without creating a GitHub account by emailing `privacytools@fire.fundersclub.com`. The subject line of your email will become the issue title. Your name will be included in the posted issue.

This repository uses [@fire-bot](https://github.com/fire-bot), [a service](https://fire.fundersclub.com) from FundersClub that converts incoming emails to GitHub issues. By sending a message to the email address above, you will be sharing your email address and message content with FundersClub. FundersClub has a privacy policy at [https://fundersclub.com/catalyst-privacy-policy/](https://fundersclub.com/catalyst-privacy-policy/) you should review before using this service. Any attachments you send via this service may be stored indefinitely by FundersClub for the purpose of making them available within the submitted GitHub issue.

You can view an example of the created issues' format at [#1444](https://github.com/privacytoolsIO/privacytools.io/issues/1444).
