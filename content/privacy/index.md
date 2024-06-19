---
title: Privacy policy
description: "This Privacy Policy governs the use and protection of personal data of Chill Utility's services, including its website and application on the Discord platform (Discord Inc.)."
layout: simple
---

{{< lead >}}
This Privacy Policy governs the use and protection of personal data of Chill Utility's services, including its website and application on the Discord platform (Discord Inc.).

This policy constitutes the contractual agreement governing the collection, use and protection of personal information of "Users", who access the services offered by Chill Utility through the website or the application. By using our services, you expressly consent to the collection, use and disclosure of your information in accordance with this Privacy Policy.
{{< /lead >}}

## Personal Data Management (Overview)

Full details of each type of personal data collected are provided in the dedicated sections of this Privacy Policy. Personal data may be freely provided by the User or, in the case of usage data, collected automatically when using the application.

In cases where the application expressly states that certain data is not mandatory, Users are free not to provide such data without consequences for the availability or operation of the service.

Users who do not know which personal data is mandatory are invited to contact the owner. Any use of tracking tools - either by the application or by the owners of third-party services used - is for the purpose of providing the service requested by the User.

Users are responsible for all third-party personal data obtained, published or shared via the application and confirm that they have the consent of the third party to provide the data to the owner.

## Detailed information on the processing of personal data

### Website

The website does not currently collect any personal data.
It is a showcase site, which does not rely on cookies or tracking tools.
Any changes will be indicated in an update to this Privacy Policy.

The full source code of the site is available here: https://github.com/chill-utility/chill-utility.github.io

### Application

#### Data stored in the Chill Utility's database

- Counter
  - Counter progress
  - Discord server ID attached to the counter progress
- `/config` command
  - Data entered in config menus and commands
- Moderation commands
  - Discord servers IDs attached to the moderation actions
  - Discord users IDs entered in moderation commands and menus
  - Discord users IDs of the users who has triggered moderation actions
  - Moderation reasons specified in moderation commands and menus
- Discord servers
  - Preferred specified via the servers' configuration
  - Servers ID
  - Amount of members on the servers

#### Intents

{{< alert "circle-info" >}}
The Discord intents are rules that explain to Discord what types of content and actions the application can see and use.
{{< /alert >}}

| Intent           | Use case                                                                                                     |
|------------------|--------------------------------------------------------------------------------------------------------------|
| Guild Members    | Moderation commands and members statistics                                                                   |
| Message Content  | Counter mini-game (reading users messages to proceed the game)                                               |
| Guilds           | Discord servers informations (like the preferred locales and servers names)                                  |
| Guild Presences  | Vanity feature (observing users status to give a role if they match an expected content)                     |
| Guild Moderation | Used to proceed bans and timeouts (to detect if a member is already sanctioned and to manage temporary bans) |

[For more technical information, you can refer to Discord's dedicated page on _Gateway Intents_.](https://discord.com/developers/docs/topics/gateway#gateway-intents)

---

This Privacy Policy was last updated on: Wednesday, June 19, 2024.
