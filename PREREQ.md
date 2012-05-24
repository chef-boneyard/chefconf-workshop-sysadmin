Chef 101 Workshop for System Administrators

This document describes the prerequisites that attendees should meet
to get the most out of the workshop.

# General Requirements

As this is a workshop for system administrators, attendees should be
familiar with basic to intermediate system administration topics
including the following:

* Command-line familiarity with Unix/Linux shells
* System resource concepts like package, service and user management
* Key-based authentication (e.g., RSA/SSH)
* Version control systems (e.g., Git, Mercurial, Subversion)
* Virtual machine hypervisor technology such as VMware or VirtualBox

Attendees should have basic working knowledge with at least one third
generation programming language such as Perl, Python, Php or Ruby.

* Basic data structures (string, numbers, array, hash or language
  equivalent)
* Conditionals (if/unless, case)
* Loops (for/foreach, while, or language equivalent)

Knowledge of Ruby is helpful, but not required.

# Workstation Requirements

Attendees should bring a wifi-enabled laptop to the workshop. The
following operating systems have been tested as *workstation systems*
with the hands on exercises:

* Ubuntu 10.04, 12.04
* Mac OS X 10.7.3
* Windows 7

Other platforms and platform versions may work without modification.
Due to time constraints we will not be able to troubleshoot issues
with unlisted platforms.

Attendees should install non-Chef required software before the workshop
starts.

* VMware Fusion, Player or Workstation **or** Oracle VirtualBox
* SSH/SCP (OpenSSH, puTTY/WinSCP or equivalent)
* [Git](http://git-scm.org)

On Unix/Linux/OS X systems:

* C/C++ compiler, build environment (`build-essential`, Xcode, or
  platform equivalent).

If Chef is not already installed, use [Opscode's Full Stack Chef
installer](http://www.opscode.com/chef/install). This will also be
covered during the introductory portion of the workshop.

## Virtual Machine Requirements

We will provide a Virtual Machine image and configuration (VMware
VMX+VMDK) of Ubuntu 12.04. It has been tested under VMware Fusion 4,
VMware Player 4 and Oracle VirtualBox 4.1.8. Other hypervisors capable
of loading and running a VMX/VMDK virtual machine may work, but we
will not be able to debug and troubleshoot. You may download the
virtual machine ahead of time as well:

If the host OS is 64 bit:

* https://s3.amazonaws.com/opscode-chef-training/opstrain-vmdk-x86_64.zip

If the host OS is 32 bit:

* https://s3.amazonaws.com/opscode-chef-training/opstrain-vmdk-i386.zip

As we're providing a VM image, the exercises will all assume Ubuntu
12.04 as the platform, with a base server installation that includes
OpenSSH running.

**Do not make modifications to the machine except as instructed in the
  workshop, as the system may be in a state that prevents completion**

Other virtual machine images or cloud provider instances may work, but
you're on your own to get that set up ahead of time.

# Chef Server Requirements

A URL to download pregenerated authentication and configuration files
will be provided during the workshop for attendees who do not have an
Opscode Hosted Chef account set up.

If you do have a Chef Server already, you're welcome to use it, but we
may not have time to troubleshoot all issues, and we do not recommend
using a server that is shared with live/production running systems.
