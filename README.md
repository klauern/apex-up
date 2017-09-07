Apex 'Up' Installation Role
=========

This is a simple role to install ['up'][https://github.com/apex/up] in your ~/bin.  It doesn't do a whole heck of a lot other than that, but it does make upgrading
easy!

Role Variables
--------------

There are really only 3 variables that you need to be aware of.  This role is not expected to run as `root`, so the user directory needs to be writable by the user running the playbook:

- `up_version` (default: `0.2.3`)
- `up_dir` (default: `~/bin`)
- `up_tmp_dir` (default: `/tmp/`)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - klauern.apex-up

License
-------

MIT
