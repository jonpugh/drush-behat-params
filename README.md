# Drush Behat Params

A basic drush plugin that calls behat with proper configuration.

Usage:

        drush @alias behat

## What?

Behat uses either hard-coded config or a JSON blob in BEHAT_PARAMS to configure what site to test.

Instead of messing with ENV vars, this plugin sets BEHAT_PARAMS for you using the Drush alias information.
