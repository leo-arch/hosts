# Hosts
NMap wrapper that binds custom hostsnames to MAC addresses instead of to IP addresses

Unlike `/etc/hosts`, which allows the user to bind a custom hostname to its IP address, Hosts allows the user to link custom hostnames to a certain MAC address. `$HOME/.config/hosts/.macs.hosts` must be filled by the user with known MAC addresses and the custom hostnames associated to them in the following form: 'xx:xx:xx:xx:xx:xx host_name'.

## Installation:

1. Clone or download this proyect (**no compilation or installtion is required**):

       $ git clone https://github.com/leo-arch/hosts

2. Cd into the `hosts` directory:

       $ cd hosts

3. Run the script:

       $ ./hosts

## Usage: 
hosts [option]
-h, --help: Show this help and exit
-p, --ports [ip_address]: Show opened ports in ip_address
-e, --edit: Edit the MAC addresses file"
With no arguments, network hosts will be listed, showing the following data: custom hostname, IP address, MAC address, and MAC vendor.
