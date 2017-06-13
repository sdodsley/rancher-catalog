# Volume plugin for Pure Storage FlashArray

Connect your Pure Storage FlashArray systems to Cattle in Rancher!

This plugin enables both provisioning and management of storage resources. Deploying this service will maintain an instance of the plugin on each of the hosts in the environment.

For more information about the plugin, see the [GitHub repository](https://github.com/PureStorage-OpenConnect/docker).

### Supported storage platforms
Any Pure Storage FlashArray system.

### Supported hosts
* RHEL / CentOS
* Ubuntu / Debian

### Configured hosts
Each host requires an iSCSI initiator and Multipathing software. See the plugin's [installation guide](https://github.com/PureStorage-OpenConnect/docker/blob/master/README.md) for more details.
