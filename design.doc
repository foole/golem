# YAML Description

* UUID (primary key, config filename)
* group id
* hostname
* num cpus
* memory
* nics
  * MAC address
  * CIDR
  * bridge interface (maybe)
  * tap device
* disks
  * disk ID
  * path to img
  * size (int)
  * type (e.g., qcow2)
* console data
  * console IP
  * console port
* metadata
  * logfile
  * snapshots
  * boot command
* installer data
  * PXE or iso
  * path to ISO
  * PXE boot command params (that aren't generated from above)
* Path to user setup script(s)?

# YAML Expectations File(s)

There could be YAML file(s) that have expectations for console actions
(key value pairs where the key action and the value is either a string
or an array of string that trigger the action)

# General design of Golem

## Create disk(s)

## Create nic(s)

## Create boot string

## Install OS

### grab install log to local machine

## Reboot to installed OS

## Run post install scripts

# Actions

Various actions can be run on a VM, up to and including a fully
automated install

* Create:
  * disk
  * nics
  * bootstring
* Install
* Run script(s)
* Snapshot
  * Save
  * Restore
  * Delete
* VM Actions
  * Start
  * Stop
  * Reboot
