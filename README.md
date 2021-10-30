# NANOG 83 Hackathon Project - Team Truthiness

This builds on a solo [project from the NANOG 82 Hackathon](https://github.com/smfeldman/nanog82hack).
In that project, I focused on bringing up [Nautobot](https://nautobot.readthedocs.io/en/latest/)
in the virtual lab environment, and using it as a source of truth to configure the virtual router instances.

For NANOG 83, my hope is to build on that by extending the ability to configure
routing on the instances based on source of truth data.  We will focus on IPv6
configuration based on the current Hackathon theme.

# Suggested sub-projects
Since team members will be distributed and have varying amounts of time available,
we will likely be working mostly separately on individual sub-projects.

These might incude:
- Develop an IPv6 addressing plan
- Configure IPv6 interfaces and/or routing
- Use GNMI/pygnmi to configure virtual routers
- Use ansible and/or nornir to configure virtual routers
- Webhook receiver to push changes from Nautobot on demand
- Use other vendor images (subject to licensing restrictions)
- Anything else even vaguely related that sounds interesting!

# Team members:
- Steve Feldman
- (add your name here!)

# Hack environment
We have been given a virtual environment running [Containerlab](https://containerlab.srlinux.dev/) and some virtual routers.
Contact Steve for instructions to access it.
We will use this git repository to make updates.

Ground rules:
- All team members have equal access.
- All work should be committed to this github repo.
- Please don't do anything which would impact other team members' work without coordination!
(We have a Slack channel which can be used for this.)  This includes making any changes to
the underlying virtual environment.
- Save your work often, in case we're not perfect about following the previous rule!
- All work is released under the [MIT license](LICENSE) and subject to the [Hackathon terms and conditions](https://www.nanog.org/legal/hackathon-terms/).
