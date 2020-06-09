README.md

ansible-playbook ios_interface.yml -e @defaults/main.yml

# Available ansible modules which can be automated 

1. ios_vrf

			vrf definition Mgmt-intf
			 !
			 address-family ipv4
			 exit-address-family
			 !
			 address-family ipv6
			 exit-address-family
			!

2. ios_system

	hostname , dns, dn search 

3. TenGigabitEthernet0/0/0.1170
1170
ny-guest
PARK_RULES
