# provision

[![Build Status](https://travis-ci.org/nytame/osx-provisioning.svg?branch=master)](https://travis-ci.org/trkw/provisioning)

## Usage
At first.

    $ sudo xcodebuild -license

and install homebrew, python, and ansible.

    $ rake setup

Run ansible-playbook.

    $ rake run

## Help
    $ rake
    rake dryrun  # Only syntax check
    rake run     # Run ansible-playbook
    rake setup   # Install homebrew, python, and ansible
