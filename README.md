### Hi there 👋

My name is Grey. I live on the beautiful west coast of Canada and I'm driven to understand how things work. This curiosity is fairly broad and ranges from the chemistry of sourdough bread, to the physics of sailing, to RAID and error-checking in data storage. In university, I studied authenticity and bringing a sense of _play_ to our everyday lives. 

In IT, I've been exploring a Linux-based self-hosted infrastructure and I've been working alongside project-coordinators to improve IT processes. From this experience, I've learned that I enjoy:

- Exploring the wonderful and wacky world of opensource software. 
- Supporting decision-makers by serving as an interface to low-level technical details.
- Designing bash scripts, documentation, processes, and diagrams as code.
- Testing bugs and establishing the steps to replicate them reliably. 
- Spending time with people who are excited to share what they're learning!


## Working together
I feel exceptionally lucky to work with opensource. I get to help maintain communal resources and witness other curious generous people doing the same. Even when describing how to replicate a bug[^1], I have a sense of contributing to something greater. I'm excited to keep learning and contributing[^2].

If you're interesting in working together, then please reach out!  (radarsymphony at protonmail dot com)

### Projects
The following are some projects I've completed for clients.
- Migrated company's email data out of google into self-hosted solution by leveraging [imapsync](https://imapsync.lamiral.info/) and bash scripting[^3].
- Migrated company [3cx VOIP system](https://www.3cx.com/) out of AWS to self-managed VPS. 
- Managed and provisioned Docker-based applications using CLI and Traefik proxy.
- Automated tasks and linked business processes with bash scripting and GUI tools like [n8n](https://n8n.io/).
- Created various bash scripts to query an [LDAP](https://www.openldap.org/) server and send emails with [msmtp](https://marlam.de/msmtp/) (e.g., confirm user info in DB, monitor mailbox size, send documents from filesystem).
- Designed a process for quickly creating infrastructure diagrams using [Structurizr](structurizr.com/) to host [C4](https://c4model.com/) inspired diagrams. This included dividing the code into modules and templates to make diagrams consistent and maintainable. 
- Designed an incident response and escalation procedure and trained team through lessons and drills.
- Designed a release-management system for monitoring and categorizing new releases into priority levels.
- Helped team members learn Linux CLI, basic docker management, and how to use [git](https://git-scm.com/) to improve their skills and support them to create their first pull requests.

### Personal Projects
Here are some of the projects I'm working on to develop my skills and improve the tech-related tools I use.
- Transition to self-hosting my data on a [Raspberry Pi](https://www.raspberrypi.com/).
- [Basic website](kryptoncode.com/) using [Hugo static site generator](https://gohugo.io/) hosted on github.io deployed by [github workflows](https://docs.github.com/en/actions).
- Setting up a [Kubernetes](https://kubernetes.io/) cluster in [Oracle's free-tier cloud](https://www.oracle.com/cloud/free/). I plan to release my steps on my blog soon.
- Refine [my custom keyboard layout](https://github.com/radarsymphony/qmk_firmware/tree/master/keyboards/ferris/keymaps/radarsymphony) (based on Colemak-DH) for better ergonomics and [i3wm](https://i3wm.org/) integration. Translate this layout into a [config file](https://github.com/radarsymphony/dotfiles/blob/main/.config/keyd/default.conf) for [Keyd](https://github.com/rvaiya/keyd) so that I can use the same keylayout for my laptop.
- Flashing opensource firmware ([ddwrt](https://dd-wrt.com/), [openwrt](https://openwrt.org/)) onto routers to enable increased networking functionality.
- Converting old chromebooks to run Linux kernal/OS.

<p align="center">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/bash/bash.png" alt="Bash" height="40" style="vertical-align:top; margin:4px">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png" alt="Python" height="40" style="vertical-align:top; margin:4px">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/php/php.png" alt="PHP" height="40" style="vertical-align:top; margin:4px">
<img src="https://github.com/traefik/traefik/raw/master/docs/content/assets/img/traefik.logo-dark.png" alt="Traefik" height="40" style="vertical-align:top; margin:4px">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/docker/docker.png" alt="Docker" height="40" style="vertical-align:top; margin:4px">
<img src="https://static.structurizr.com/img/favicon.png" alt="Structurizr" height="40" style="vertical-align:top; margin:4px">
<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/vim/vim.png" alt="Vim" height="40" 
style="vertical-align:top; margin:4px">
<img src="https://i3wm.org/favicon.ico" alt="i3wm" height="40" style="vertical-align:top; margin:4px">
</p>


[^1]: Example bug reports: [Bookstack](https://github.com/BookStackApp/BookStack/issues/3477) [Nextcloud](https://github.com/nextcloud/richdocuments/issues/2941) [Freescout](https://github.com/freescout-helpdesk/freescout/issues/2189)
[^2]: I'm intrigued by how the opensource community manages these common resources. In my day-to-day, I'm asking: How does the opensource community mitigate "the tragedy of the commons" and how is it still susceptible? What takeaways are useful in others areas of life? Yes, these "resources" are digital and perhaps not constrained by the same laws that govern natural resources. But they are resources that take maintenance and management. They require people to coordinate and communicate. And the health of the resource is often dependent on how people give back. 
[^3]: I was later able to use Imapsync and bash scripting to salvage imap data from a corrupted MariaDB instance.

