# provisioning

[![Build Status](https://travis-ci.org/trkw/provisioning.svg?branch=master)](https://travis-ci.org/trkw/provisioning)

## Usage
At first.

    $ sudo xcodebuild -license

![xcodebuild](https://cloud.githubusercontent.com/assets/2557813/12369385/7b0b3e72-bc39-11e5-8c40-3e39c4e58a46.png)


and install homebrew, python, and ansible.

    $ rake setup

Run ansible-playbook.

    $ rake run

## Help
    $ rake
    rake dryrun  # Only syntax check
    rake run     # Run ansible-playbook
    rake setup   # Install homebrew, python, and ansible
