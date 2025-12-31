# komodo-backup
Backup and restore functionality for [Komodo](https://github.com/moghtech/komodo/).

## Concept

The general idea is to go through all stacks, services and volumes and using a custom defined solution to back them up.
But resources can be skipped using tags.

## Installation

Easiest way to install is adding this repository to Komodo as `Sync`. It will add two actions (backup, restore) and one procedure (scheduled daily backup). 
