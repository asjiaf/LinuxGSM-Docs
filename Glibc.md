# Summary
Most servers require a specific version of Glibc installed. Newer distros normally have the required version. Check the requirements below.

Server Requirements
===================

A list of all the servers GLIBC requirements

| Game Server                      | GLIBC   |
|----------------------------------|---------|
| 7 Days to Die                    | n/a     |
| ARMA 3                           | 2.13    |
| Blade Symphony                   | 2.15    |
| Counter Strike: Condition Zero   | 2.07    |
| Counter Strike: Global Offensive | 2.07    |
| Counter Strike 1.6               | 2.07    |
| Counter Strike: Source           | 2.07    |
| Day of Defeat                    | 2.07    |
| Day of Defeat: Source            | 2.07    |
| Deathmatch Classic               | 2.07    |
| Double Action: Boogaloo          | 2.15    |
| Fistful of Frags                 | 2.15    |
| Garry's Mod                      | 2.15    |
| Half Life: Deathmatch            | 2.07    |
| Half-Life: Opposing Force        | 2.07    |
| Half Life 2: Deathmatch          | 2.07    |
| Insurgency                       | 2.15    |
| Just Cause 2                     | 2.13    |
| Killing Floor                    | n/a     |
| Left for Dead                    | 2.07    |
| Left for Dead 2                  | 2.07    |
| Mumble                           | n/a     |
| Natural Selection 2              | 2.15    |
| No More Room in Hell             | 2.15    |
| Red Orchestra: Ostfront 41-4     | n/a     |
| Ricochet                         | 2.07    |
| Serious Sam 3:BFE                | 2.13    |
| Starbound                        | n/a     |
| Team Fortress: Classic           | 2.07    |
| Team Fortress 2                  | 2.07    |
| Unreal Tournament 2004           | n/a     |
| Unreal Tournament 99             | n/a     |

Disto glibc
===========

List of distros and there glibc version. [distrowatch.com][] is also a great source to find this infomation.

| Distro           | glibc   |
|------------------|---------|
| CentOS 6         | 2.12    |
| CentOS 7         | 2.17    |
| Debian 6         | 2.11.2  |
| Debian 7         | 2.13    |
| Ubuntu 12.04 LTS | 2.15    |
| Ubuntu 14.04 LTS | 2.19    |

glibc fixes
===========

Many of the servers can work on distros with older _Glibc_ versions by using the _Glibc_ fixes that are available with LGSM. This simply copies the required files to the `serverfiles` directory. Many game servers will look for there dependencies in there serverfiles directory. Even if your dedicated server does not meet the glibc requirement the server may still work. The following servers have a glibc fix available for it.

-   ARMA 3
-   Blade Symphony
-   Double Action: Boogaloo
-   Fistful of Frags
-   Garry's Mod
-   Insurgency
-   Just Cause 2
-   Natural Selection 2
-   No More Room in Hell
-   Serious Sam 3: BFE

External Links
==============

  [distrowatch.com]: http://distrowatch.com/
  [Glibc Homepage]: http://www.gnu.org/software/libc/