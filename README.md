# Puppet on Windows 

## Overview

This module acts as a collection for the Puppet Forge's best Windows content. Installing puppetlabs-windows will install a variety of great modules from a diverse group of module authors, including Puppet Labs. Many are contributed by our community, reviewed and recommended by Puppet Labs as [Puppet Approved](https://forge.puppetlabs.com/approved) modules. Several critical modules are provided through our [Puppet Supported](https://forge.puppetlabs.com/supported) program.

### Quick Start

This guide assumes that you have installed Puppet Enterprise on your Windows server and that you've connected its Puppet agent to a Puppet Enterprise master. 
- [Learn more](https://docs.puppetlabs.com/pe/latest/install_windows.html) on installing the Puppet Enterprise agent onto a Windows server.
- Don't have a PE master? Try the [Learning Puppet VM](https://docs.puppetlabs.com/learning/introduction.html#get-the-free-vm) for evaluation purposes.

*We should use this section to get a new Windows user from nothing to functional PE managing a Windows box. Is it just a write-up of running the learning VM on a Windows desktop, connecting a windows PE agent to the VM? We may want to eventually offer PE node manager artifacts that the customer can import into their console* 


## The Puppet on Windows Collection

This README briefly describes each included module by category of use. Full documentation for each module can be found by following links to individual module pages.

Take note that only the modules by Puppet Labs are supported with Puppet Enterprise. The rest have been reviewed and recommended by Puppet Labs but are not eligible for commercial support.


*The spirit of this section is to list out our capabilities, emphasis on Windows key words, followed by example DSL on how they're used to accomplish a cohesive thing. Obviously, the DSL part is to-do. Ryan failed to get a Windows VM running properly in time.*

### Core Windows

Use Puppet on Windows to:
- Read, create and write **registry keys** with [puppetlabs-registry](https://forge.puppetlabs.com/puppetlabs/registry).
- Interact with **PowerShell** through the Puppet DSL with [puppetlabs-powershell](https://forge.puppetlabs.com/puppetlabs/powershell).
- **Reboot** Windows as part of management as necessary through [puppetlabs-reboot](https://forge.puppetlabs.com/puppetlabs/reboot).
- Install or remove **Windows features** with [opentable-windowsfeature](https://forge.puppetlabs.com/opentable/windowsfeature).
- Download files for use during management via [opentable-download_file](https://forge.puppetlabs.com/opentable/download_file).
- Enforce fine-grained **access control** permissions using [puppetlabs-acl](https://forge.puppetlabs.com/puppetlabs/acl).

*Example Usage: Should include some sample DSL from these modules which when used together, provide a useful end-result.* 

### Web Sites & Services

Use Puppet on Windows to:
- Create and manage Microsoft SQL including databases, users and grants with puppetlabs-mssql.
- Build IIS sites and virtual applications with [opentable-iis](https://forge.puppetlabs.com/opentable/iis).

*Example Usage: Should include some sample DSL from these modules which when used together, provide a useful end-result.* 


POTENTIAL ADDITIONS (to be approved or purged from this collection)

More utility modules:
https://forge.puppetlabs.com/liamjbennett/win_facts
https://forge.puppetlabs.com/liamjbennett/windows_autoupdate
https://forge.puppetlabs.com/opentable/sslcertificate
https://forge.puppetlabs.com/counsyl/windows

Active directory interactions:
https://forge.puppetlabs.com/jriviere/windows_ad/readme
https://forge.puppetlabs.com/martezr/windows_domain_controller
https://forge.puppetlabs.com/trlinkin/domain_membership

Remote administration and logging:
https://forge.puppetlabs.com/martezr/rdp
https://forge.puppetlabs.com/liamjbennett/windows_eventlog

Package & file utility: 
https://forge.puppetlabs.com/jriviere/windows_isos
https://forge.puppetlabs.com/creativeview/mssql_system_dsn
https://forge.puppetlabs.com/ceritsc/chocolatey_sw


AND MANY MORE (link to search for windows)


ADDITIONAL RESOURCES

- PuppetConf Talks
- Windows documentation

## Limitations

- this section could express the distinction between supported/approved and speak to the requirements for getting started with windows in general (need a master). 

## Development

- follow each individual module's project url link. 

