Introduction
============

This is a containerized version of the [Addict Active Directory REST API](https://github.com/dthree/addict/).

Environment Variables
=====================

This section describes all of the environment variables that can be used to
customize the behavior of this container. Please override them with values
specific to your configuration.

- `ADDICT_URL` - LDAP server URL (example: "ldaps://ldap.example.com")
- `ADDICT_USER` - LDAP server username (example: "admin@example.com")
- `ADDICT_PASS` - LDAP server password (example: "supersecret")
