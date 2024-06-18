This script configures an already existing server for a cPanel install. It is designed to do all the prerequisites that cPanel requires on rhel-based servers, without failing on non rhel-based servers

To run ad-hoc:

use your package manager to install ansible-core, and then cd to the cPanel_intall directory and run "ansible-playbook site.yml"

If you want verbose output for troubleshooting, add a --verbose flag to the command