# Better VVV performance on Mac
Fork of vvv 1.2-working config files

- Adds nfs support for main shared folder for faster folder synchronization
	- Custom mount options allow for instantaneous(<500ms) sync between host and guest (cool for grunt watchers)
- Forward ports for livereload

## Things to do manually
- To speed up the vagrant up process, do this https://github.com/mitchellh/vagrant/wiki/%60vagrant-up%60-hangs-at-"Waiting-for-VM-to-boot.-This-can-take-a-few-minutes"