## Helpful Commands

- `chef --version`{{execute}}
- `chef-client --help`{{execute}}
- `chef-client --local-mode default.rb`{{execute}}
- `chef-shell`{{execute}}
- `ohai | less`{{execute}}

## Helpful Links

- [An Overview of Chef](https://docs.chef.io/chef_overview.html)
- [Learn Chef](https://learn.chef.io)
- [Chef Docs](https://docs.chef.io)
- [Chef Community Slack](https://community-slack.chef.io)
- [Chef Mailing List](https://discourse.chef.io)

## Deploy Example

You have a small [recipe](https://docs.chef.io/recipes.html) example in the *default.rb* file:

`cat default.rb`{{execute}}

Try running it:

`chef-client --local-mode default.rb`{{execute}}

This example should have generated a [MOTD](https://en.wikipedia.org/wiki/Motd_(Unix) file:

`cat /etc/motd`{{execute}}
