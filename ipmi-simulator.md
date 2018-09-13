# ipmi simulator MEMO


| Discussion: Having issues with ipmitool sol activate towards ipmi_sim  |
http://openipmi-developer.narkive.com/7WRyU4Ub/having-issues-with-ipmitool-sol-activate-towards-ipmi-sim  |

## InfraSIM
InfraSIM github
https://github.com/InfraSIM

nfraSIM provides data center scale infrastructure simulation https://infrasim.readthedocs.io
https://github.com/InfraSIM/InfraSIM

InfraSIM allows you to deploy virtualized infrastructures consisting of simulated servers, 
storage devices, switches and smart PDUs(Power Distribute Units). 
You can use it to create development environments that simulate the exact physical environments 
where your product will eventually be deployed.
https://infrasim.readthedocs.io/en/latest/

Infrasim-compute: bare-metal server simulator
https://github.com/InfraSIM/infrasim-compute
> Notice: You can use VNC to access the emulated legacy hardware, the default VNC port is 5901

InfraSIM Virtual Network;;  A tool to setup two-layer vswitches and network namespaces.
https://github.com/InfraSIM/infrasim-network

vRackSystem is a tool to easily build a virtual Rack. Please follow below document to setup the vracksystem server.
https://github.com/InfraSIM/vracksystem


## netbox : IPAM
https://github.com/digitalocean/netbox/releases

https://github.com/digitalocean/netbox/issues/1804

Can we lockdown the visibility of netbox IPAM only after we log in?
https://www.digitalocean.com/community/questions/can-we-lockdown-the-visibility-of-netbox-ipam-only-after-we-log-in


NetBox from Digital Ocean
https://www.sdxcentral.com/projects/netbox/reports/2017/open-source-networking/

Setting up NetBox on OpenBSD
Posted on Sat 12 May 2018 
https://blog.jasper.la/setting-up-netbox-on-openbsd.html

How to install NetBox on Ubuntu 18.04 /Ubuntu 16.04
https://computingforgeeks.com/how-to-install-netbook-on-ubuntu16test-environment/

Netbox – DCIM et IPAM libre – Gérez votre infrastructure et votre réseau
Posted By Pierre-Yves Dubreucq on Oct 11, 2017
http://blog.admin-linux.org/administration/netbox-solution-dcim-ipam-libre

netboxapi-client 0.1b1 
https://pypi.org/project/netboxapi-client/

Package netbox provides an API client for DigitalOcean's NetBox IPAM and DCIM service. 
https://github.com/digitalocean/go-netbox

NetConfig : Netbox Integration (Network Switch)
https://netconfig.readthedocs.io/en/latest/netbox-integration.html


## openipmi
ipmi_sim_chassiscontrol
http://qemu.11.n7.nabble.com/ipmi-sim-chassiscontrol-td553067.html

gist: IPMI simulator ; install and configuration
https://gist.github.com/bot11/a34ff0008cae75bd662d

IPMI abstraction layer, this is here so I can run Coverity scans on it 
https://github.com/cminyard/openipmi

Fake IPMI server based on conpot and pyghmi https://pypi.python.org/pypi/ipmisim
https://github.com/rhtyd/ipmisim

ipmi_sim in a minimal Docker container
https://github.com/vapor-ware/ipmi-simulator
