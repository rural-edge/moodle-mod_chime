# Intro

Chime is the web and app based video conferencing service (http://chime.aws). This
plugin offers tight integration with Moodle, supporting meeting creation,
synchronization, grading, and backup/restore.

# Prerequisites

This plugin is designed for Chime Pro accounts.

To connect to the Chime APIs this plugin requires an account level JWT app to be
created. To create an account-level JWT app the Developer Role Permission is
required.

You will need to create a API Key and that will generate the API key and secret.
https://docs.aws.amazon.com/chime/latest/APIReference/Welcome.html

## Installation

1. Install plugin to mod/chime. More details at https://docs.moodle.org/39/en/Installing_plugins#Installing_a_plugin
2. Once you install the plugin you need to set the following set the following
   settings to enable the plugin:

- Chime API key (mod_chime | apikey)
- Chime API secret (mod_chime | apisecret)
- Chime home page URL (mod_chime | chimeurl), Link to your organization's custom Chime landing page.

Please note that the API key and secret is not the same as the LTI key/secret.

If you get "Access token is expired" errors, make sure the date/time on your
server is properly synchronized with the time servers.

## Changelog

v1.0

- Initial release
