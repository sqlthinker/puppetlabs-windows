# Puppet on Windows

## Overview

This module acts as a pack of the Puppet Forge's best Windows content. Installing puppetlabs-windows will install a variety of great modules from a diverse group of module authors, including Puppet Labs. Many are contributed by our community, reviewed and recommended by Puppet Labs as [Puppet Approved](https://forge.puppetlabs.com/approved) modules. Several core modules are provided through our [Puppet Supported](https://forge.puppetlabs.com/supported) program.

## Setup

This guide assumes that you have downloaded and installed Puppet Enterprise on your Windows server and that you've connected its Puppet agent to a Puppet Enterprise master.
- [Learn more](https://docs.puppetlabs.com/pe/latest/install_windows.html) on installing the Puppet Enterprise agent onto a Windows server.
- Don't have a PE master? Try the [Learning Puppet VM](https://docs.puppetlabs.com/learning/introduction.html#get-the-free-vm) for evaluation purposes.

Once installed, start by installing the windows module pack onto your PE master (like the Learning VM) by running `puppet module install puppetlabs-windows` from the command-line. You should see the Puppet module tool installing multiple modules from the Puppet Forge. [Learn more](https://docs.puppetlabs.com/puppet/latest/reference/modules_installing.html#installing-from-the-puppet-forge) about installing modules.

Now, you can start using individual modules from this pack to solve a problem. To do this, you'll want to browse the documentation for an individual module listed below. Equipped with details on interacting with individual module capabilities, you may want to [write your own module](https://docs.puppetlabs.com/pe/latest/quick_writing_windows.html) or [directly assign work](https://docs.puppetlabs.com/pe/latest/console_classes_groups.html) to your Windows machine from the Puppet Enterprise console.

## The Puppet on Windows Pack

These are the modules available in the puppetlabs-windows pack. Full documentation for each module can be found by following links to individual module pages. By installing puppetlabs-windows, you will install recommended versions of the entire set of Puppet modules.

Take note that only the modules by Puppet Labs are supported with Puppet Enterprise. The rest have been reviewed and recommended by Puppet Labs but are not eligible for [commercial support](http://puppetlabs.com/services/customer-support).

Use Puppet on Windows to:
- Read, create and write **registry keys** with [puppetlabs-registry](https://forge.puppetlabs.com/puppetlabs/registry).
- Interact with **PowerShell** through the Puppet DSL with [puppetlabs-powershell](https://forge.puppetlabs.com/puppetlabs/powershell).
- **Reboot** Windows as part of management as necessary through [puppetlabs-reboot](https://forge.puppetlabs.com/puppetlabs/reboot).
- Enforce fine-grained **access control** permissions using [puppetlabs-acl](https://forge.puppetlabs.com/puppetlabs/acl).
- Install or remove **Windows features** with [puppet-windowsfeature](https://forge.puppetlabs.com/puppet/windowsfeature).
- Download files for use during management via [puppet-download_file](https://forge.puppetlabs.com/puppet/download_file).
- Build IIS sites and virtual applications with [puppet-iis](https://forge.puppetlabs.com/puppet/iis).
- Install packages with [chocolatey-chocolatey](https://forge.puppetlabs.com/chocolatey/chocolatey).
- Create and manage Microsoft SQL including databases, users and grants with the [puppetlabs-sqlserver](https://forge.puppetlabs.com/puppetlabs/sqlserver) module (installed separately).


## More from the Puppet Forge

You can find even more great modules by [searching for windows](https://forge.puppetlabs.com/modules?utf-8=✓&sort=rank&q=windows). Here are a few examples from the Puppet community.

- [puppet-windows_autoupdate](https://forge.puppetlabs.com/puppet/windows_autoupdate)
- [puppet-windows_eventlog](https://forge.puppetlabs.com/puppet/windows_eventlog)
- [puppet-sslcertificate](https://forge.puppetlabs.com/puppet/sslcertificate)
- [counsyl-windows](https://forge.puppetlabs.com/counsyl/windows)
- [ceritsc-chocolatey_sw](https://forge.puppetlabs.com/ceritsc/chocolatey_sw)
- [jriviere-windows_ad](https://forge.puppetlabs.com/jriviere/windows_ad)
- [trlinkin-domain_membership](https://forge.puppetlabs.com/trlinkin/domain_membership)

These modules are not part of this pack nor are they Puppet Approved or Puppet Supported.
But, every Forge module now offers [quality and community ratings](http://puppetlabs.com/blog/new-ratings-puppet-forge-modules) to help you choose the best module for your need.
