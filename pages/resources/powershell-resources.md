---
layout: page
title: A Journey to the Powershell Citadel
subtitle: All important places you need to know for learning.
permalink: "powershell-resources"
excerpt: "This page represents my favorite list of powershell resources. When you start learning a new language you
often get confused by all the different guides, standards and best practices. So I started collecting all important
sources you need to know."
image: "/img/image/ps-journey.jpg"
show-avatar: true
bigimg:	# /path/to/img - or multiple entries <- "Path": "Description">
  - "/img/bigimg/res-posh.jpg" : "Photo by Eugenio Mazzone on Unsplash"
category: Resources
tags: [Powershell]
googlefonts: ["Share+Tech+Mono"]
comments: true
# custom page vars
edit: "21-11-2017"
---

{% include about.html footer=true readingtime=true%}

# The Journey Begins now young Novice

In this section you find the most basic stuff. It's aimed to help beginners who just got in touch with powershell.
All external links refer to the latest production ready Powershell version. This is currently the version `5.1`.

* [Official Documentation] - Microsoft recently moved all the Powershell documentation to [docs.microsoft.com].
* [Powershell Reference] - If you need details about a specific function or cmdlets you can find it there. The
  Reference is grouped by the built in modules. You can expand each group and select the individual help page of
  each function.
* [About Pages] - The docs does not only contain a reference of all the built in functions. It also contains the so
  called *About* pages. These pages explain specific concepts and language related topics. You can find them in a
  separate *about* section of the **Microsoft.PowerShell.Core** module reference. The titles always starts with
  *about_* and the specific name.

[Official Documentation]: https://docs.microsoft.com/en-us/powershell
[docs.microsoft.com]: https://docs.microsoft.com
[Powershell Reference]: https://docs.microsoft.com/en-us/powershell/scripting/powershell-scripting?view=powershell-5.1
[About Pages]: https://docs.microsoft.com/de-de/powershell/module/microsoft.powershell.core/about/about_aliases?view=powershell-5.1

{: .box-note}
<i class="fa fa-commenting icon-blue" aria-hidden="true"></i> **NOTE:** You can also display the *about_* pages with
a powershell function itself. To get a list of all about pages just use `Get-Help about_*`. All you need to to is pick
a topic name and use the function again like this: `Get-Help about_Functions`.

## Start using it!

You can't learn Powershell like every other language if you don't use it. So try to solve basic tasks with Powershell.
Google around or ask questions in communities like:

* [StackOverflow](https://stackoverflow.com/questions/tagged/powershell)
* [Powershell.org](https://powershell.org/forums)

# Acolyte
Once you got familiar with the basic powershell concepts start discovering advanced techniques like *functions*,
*modules*, *classes*, *types*, *Extended Type System*, *Powershell Remoting*, *jobs*, *Package Management*.

## It's all about the style!

As soon as you managed to spell `Powershell` please respect the [PowerShell Best Practices and Style Guide](https://github.com/PoshCode/PowerShellPracticeAndStyle).
Unfortunately there is no standard *PEP8* in python, but this is the most respected and active one. Trust me - it's
maintained by all the experts out there. Just read it, understand it, adopt it and use whatever you can.

{: .box-warning}
<i class="fa fa-bolt icon-yellow" aria-hidden="true"></i> **IMPORTANT:** There is nothing worse than reading an ugly
 piece of code. And yes, it works but it's impossible to read, understand, review, maintain and makes no fun!

## Important Modules

* [PSScriptAnaylzer] - Static code checker for PowerShell modules and scripts.
* [Pester] - Test and mock framework
* [platyPS] - Write PowerShell External Help in Markdown.

[PSScriptAnaylzer]: https://github.com/PowerShell/PSScriptAnalyzer
[Pester]:https://github.com/pester/Pester
[platyPS]: https://github.com/PowerShell/platyPS

## Tools

In this phase you should also start working with additional tools like:

* VCS (Version Control System):
  * [Git-SCM](https://git-scm.com/)
* additional Editors, IDEs:
  * [Visual Studio Code](https://code.visualstudio.com/)
* CI/CD Environments:
  * [Github](https://github.com/)
  * [Phabricator](https://www.phacility.com/phabricator/)
  * [Jenkins](https://jenkins.io/)
  * [AppVeyor](https://www.appveyor.com/)
  * [GoCD](https://www.gocd.org/)
* Helper
  * [ILSpy](http://ilspy.net/)
* Coverage Reports
  * [Coveralls.io](https://coveralls.io/)

{: .box-note}
<i class="fa fa-commenting icon-blue" aria-hidden="true"></i> **NOTE:** If you develop open source projects I
recommend using [Github](https://github.com/) in combination with [AppVeyor](https://www.appveyor.com/). You don't
need to maintain any additional infrastructure and they are free for public repositories. Otherwise I like working
with Phabricator as *Git Server* and project coordination. If you take this path you definitely need a build server
like Jenkins.

# Maester

Now you mastered the Powershell concepts, know advanced stuff like Powershell remoting, Desired Sate Configuration
and important additional modules. Now it's important to keep up to date and network. Get input from others and
spread the work of powershell while teaching others!

## Gran Master Blogs

* [dille.name](http://dille.name) - An awesome Germany based DevOps Engineer and Docker Captain with outstanding
  Microsoft and Powershell knowledge.
* [DonJones.com](https://donjones.com/) - If you never heard about DonJones I can't help you. He is one of the biggest
  maesters in the Powershell citadel and a great inspiration.
* [Kevin Marquette on PowerShell Theory](https://kevinmarquette.github.io/) - A great blog about various Powershell
  topics.
* [rkeithhill.wordpress.com](rkeithhill.wordpress.com) -
* [xainey.github.io](https://xainey.github.io//)- Michael Willis blog contains great articles about powershell classes,
  module creation and building frontend for powershell. It's high quality content and easy to follow expert topics.

## Get in touch with the Archmaesters

Take a look at the [PowerShell Slack Team](http://slack.poshcode.org/) if your searching other active powershell experts.

# Additional Resources

* [Writing Modules]- Resources for writing Powershell Modules. from
  *Writing PowerShell Modules: Tips, Tools, and Best Practices session at the 2017 PowerShell + DevOps Global Summit*
* [Awesome Powershell] - A curated list of delightful PowerShell packages and resources.

[Writing Modules]: https://github.com/RamblingCookieMonster/WritingModules
[Awesome Powershell]: https://github.com/janikvonrotz/awesome-powershell
