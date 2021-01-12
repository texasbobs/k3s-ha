# k3s-ha

Automated k3s deployments using embedded etcd.

# Install with k3s-ha

1. setup inventory:

	Look at the [example_inventory.yml](example_inventory.yml) to see how you could set your cluster up.

2. run playbook to install:
	```
	time ansible-playbook -i ./inventory.yml -u root ./k3s.yml
	```
