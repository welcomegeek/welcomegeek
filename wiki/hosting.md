# Hosting Services

## Requirements for listing

  * Provider needs to accept new users
  * If the provider is invite-only, you should specify it in the notes section
  * Paid-only providers need to have "paid-only" included in the notes section

## Known to be compatible

|Provider|Tested/Revisited|Notes|
|:--|:--|:--|
|[FreeHostingEU.com](https://freehostingeu.com)|[2018-04-18](http://fheutest.cyb) by [albino](https://wiki.opennic.org/user/albino)|Requires a workaround, therefore not recommendable; see [here](http://fheutest.cyb) for details.|
|[GitHub Pages](https://pages.github.com)|[2018-04-10](http://albino.cyb) by [albino](https://wiki.opennic.org/user/albino)|See 'A record' instructions [here](https://help.github.com/articles/setting-up-an-apex-domain/). More info [here](http://albino.cyb).|
|[Surge](https://surge.sh)|[2018-04-18](http://ankit.libre) by [ankit](https://wiki.opennic.org/user/ankit)|Requires Nodejs based command line client to upload static websites.[Documentation](https://surge.sh/help). See [http://ankit.libre](http://ankit.libre).|
|[Uberspace.de](https://uberspace.de/)|[2018-04-10](https://wiki.uberspace.de/webserver:https#technische_hintergruende) by [fusl](https://wiki.opennic.org/user/fusl)|Website and panel are only available in German language \\ [Flexible pricing, minimum price is €1 per month](https://uberspace.de/prices)|
|[Vercel](https://vercel.com/)|[2021-11-26](http://giscus.some.geek/) by [luqaska](/user:luqaska)|Works fine with CNAME records, but didn't try with NS ones|
|Tested at [Interserver.net](https://interserver.net), should work as well with any CPanel hosting|[2019-04-29](http://libre.libre) by [antihierarchic](https://wiki.opennic.org/user/antihierarchic)|Interserver.net itself doesn't allow to create non-ICANN domains through its own DNS manager, but: log into CPanel - add Domain (A record is created, check CPanel Zone editor), then add this A record for the domain in OpenNic registration panel - tested and works with be.libre (.dyn, .geek, .gopher, .indy, .libre, .oss, .parody -all exept .pirate - don't know why)|

## Known to be incompatible

|Provider|Tested/Revisited|Notes|
|:--|:--|:--|
|[Aternos](https://aternos.org/)|2021-11-26 by [luqaska](/user:luqaska)| Minecraft server hosting|
|[bplaced](https://www.bplaced.net/)|2018-04-10 by [fusl](https://wiki.opennic.org/user/fusl)||
|[FreeFlarum](https://freeflarum.com/)|2021-11-25 by [luqaska](/user:luqaska)| Flarum forum hosting \\ [They're not planning adding support to OpenNIC domains](https://github.com/gwillem/freeflarum.com/issues/298)|
|[FreeWHA](https://www.freewebhostingarea.com/)|2018-04-13 by [albino](https://wiki.opennic.org/user/albino)||
|[InfinityFree](https://infinityfree.net/)|2021-11-26 by [luqaska](/user:luqaska)||
|[lima-city](https://www.lima-city.de/)|2018-04-10 by [fusl](https://wiki.opennic.org/user/fusl)|Website and panel are only available in German language|
|[Replit](https://replit.com/)|2021-11-23 by [luqaska](/user:luqaska)||
|[Square7](https://www.square7.ch/)|2018-04-10 by [fusl](https://wiki.opennic.org/user/fusl)||
|[x10hosting](https://x10hosting.com/)|2018-04-13 by [albino](https://wiki.opennic.org/user/albino)||

## Not tested yet

|Provider|Notes|
|:--|:--|:--|
|[000webhost](https://000webhost.com/)||
|[Amazon Web Services](https://aws.amazon.com/)||
|[GitLab Pages](https://docs.gitlab.com/ee/user/project/pages/)||
|[Firebase](https://firebase.google.com/)||
|[Google Cloud](https://cloud.google.com/)||
|[Heroku](https://heroku.com/)| You can only set up a custom domain after linking your credit card to your account|
|[PythonAnywhere](https://www.pythonanywhere.com/)|Only works with Python apps|
|[Hostinger](https://www.hostinger.com/)||
|[Wiroos](https://wiroos.com/)|Website only available in Spanish|

------

[![CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)

Fork of ["OpenNIC Compatible Webspace Providers"](https://wiki.opennic.org/webspaceproviders) from [OpenNIC's official wiki](https://wiki.opennic.org)
