# Welcome! 👋

Welcome to 2i2c's organisation to manage access to our demo hubs!

## About this organisation

Many of 2i2c's JupyterHubs use GitHub as an OAuth provider, and we can manage
who is authorised to access our hubs by scoping to specific GitHub organisations
or teams within an organisation. Occasionally, we run demos and would like to
give access to a specific hub to groups of folk relatively easily. This
organisation exists as a space where we can do that without worrying too much
about the security implications if we were to add everyone to our main
[2i2c org](https://github.com/2i2c-org).

## How 2i2c staff should use this repo

All 2i2c staff members should be Owners of this organisation, with the ability
to invite external collaborators as they see fit. They should create new teams
as needed and add GitHub user accounts that they want to grant access to a demo
hub to.

## Org-wide or teams-based auth?

Hubs can be scoped to allow users from a specific GitHub org, or a specific team.
Best practice here is to have roughly a 1:1 mapping of demo hubs to GitHub teams
(in this org) that permit access to that demo hub, and then set up the demo hub
to have the appropriate [teams-based authentication](https://infrastructure.2i2c.org/hub-deployment-guide/configure-auth/github-orgs/).

While org-wide authentication is not explicitly forbidden, please be aware that
_anyone added to the organisation will have access to all hubs that permit this
organisation_.
