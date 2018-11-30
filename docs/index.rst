.. RTD Test Project documentation master file, created by
   sphinx-quickstart on Mon Oct 22 15:43:38 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

*************
RTD Test Docs
*************

Welcome to RTD Test Project's documentation!
============================================

Cumulus Linux is the first full-featured Linux operating system for the
networking industry. The `Debian
Jessie <https://www.debian.org/releases/jessie/>`__-based,
networking-focused distribution runs on hardware produced by a `broad
partner ecosystem <http://cumulusnetworks.com/hcl/>`__, ensuring
unmatched customer choice regarding silicon, optics, cables, and
systems.

This user guide provides in-depth documentation on the Cumulus Linux
installation process, system configuration and management, network
solutions, and monitoring and troubleshooting recommendations. In
addition, the quick start guide provides an end-to-end setup process to
get you started.

What's New in Cumulus Linux 3.7
===============================

Cumulus Linux 3.7 contains a number of new platforms, features and
improvements:

-  New `platforms <https://cumulusnetworks.com/hcl>`__ include:
   -  QCT QuantaMesh BMS T4048-IX8 (25G Trident 3)
   -  QCT QuantaMesh BMS T7032-IX7 (100G Trident 3)
   -  Dell S5248F-ON (25G Trident 3)
   -  Penguin Arctica 4806xt (10G Trident 2+)
-  `Line side
   loopback <https://docs.cumulusnetworks.com/display/DOCS/Facebook+Voyager+Optical+Interfaces#FacebookVoyagerOpticalInterfaces-lineSideLoopback>`__
   and `Terminal
   loopback <https://docs.cumulusnetworks.com/display/DOCS/Facebook+Voyager+Optical+Interfaces#FacebookVoyagerOpticalInterfaces-terminalLoopback>`__
   mode for Facebook Voyager troubleshooting
-  `OVSDB Server High Availability (Early
   Access) <https://docs.cumulusnetworks.com/display/DOCS/OVSDB+Server+High+Availability>`__
-  `RADIUS Change of Authorization (CoA)
   requests <https://docs.cumulusnetworks.com/display/DOCS/802.1X+Interfaces#id-802.1XInterfaces-CoArequests>`__
-  `RADIUS AAA local fallback
   authentication <https://docs.cumulusnetworks.com/display/DOCS/RADIUS+AAA#RADIUSAAA-local-fallback-auth>`__
-  `TACACS+ local fallback
   authentication <https://docs.cumulusnetworks.com/display/DOCS/TACACS+Plus#TACACSPlus-fallback-auth>`__
-  EVPN enhancements
   -  `Neighbor Discovery (ND) Extended
      Community <https://docs.cumulusnetworks.com/display/DOCS/Ethernet+Virtual+Private+Network+-+EVPN#EthernetVirtualPrivateNetwork-EVPN-ND_extended_community>`__
      support
   -  `Extended
      mobility <https://docs.cumulusnetworks.com/display/DOCS/Ethernet+Virtual+Private+Network+-+EVPN#EthernetVirtualPrivateNetwork-EVPN-MAC-mobility>`__
      support
   -  ECMP support for overlay networks on RIOT-capable Broadcom switches
-  New NCLU commands:
   -  `Show the version of a
      package <https://docs.cumulusnetworks.com/display/DOCS/Adding+and+Updating+Packages#AddingandUpdatingPackages-versionDisplay>`__
   -  `Show the interface description
      (alias) <https://docs.cumulusnetworks.com/display/DOCS/Interface+Configuration+and+Management#InterfaceConfigurationandManagement-show_alias>`__
      for all interfaces on the switch
   -  `Show which interfaces are in a
      VRF <https://docs.cumulusnetworks.com/display/DOCS/Virtual+Routing+and+Forwarding+-+VRF#VirtualRoutingandForwarding-VRF-vrf-interfaces>`__
      and the `VNIs for VRF
      interfaces <https://docs.cumulusnetworks.com/display/DOCS/Virtual+Routing+and+Forwarding+-+VRF#VirtualRoutingandForwarding-VRF-vrf-interfaces>`__
   -  `Change bond mode to IEEE
      802.3ad <https://docs.cumulusnetworks.com/display/DOCS/Bonding+-+Link+Aggregation>`__
      link aggregation mode

For information on bug fixes and known issues present in this release,
refer to the `product release
notes <https://support.cumulusnetworks.com/hc/en-us/articles/360007793174-Cumulus-Linux-3-7-Release-Notes>`__.

Open Source Contributions
=========================

To implement various Cumulus Linux features, Cumulus Networks has forked
various software projects, like CFEngine, ``Netdev`` and some Puppet
Labs packages. The forked code resides in the Cumulus Networks `GitHub
repository <https://github.com/CumulusNetworks>`__.

Cumulus Networks has also developed and released new applications as
open source. The list of open source projects is on the `open source
software <http://oss.cumulusnetworks.com/>`__ page.

Hardware Compatibility List
===========================

You can find the most up-to-date hardware compatibility list (HCL)
`here <https://cumulusnetworks.com/hcl/>`__. Use the HCL to confirm that
your switch model is supported by Cumulus Networks. The HCL is updated
regularly, listing products by port configuration, manufacturer, and SKU
part number.

Download the User Guide
=======================

You can download the current Cumulus Linux User Guide, as well as
previous versions, in PDF format:

-  `Cumulus Linux 3.7.0 User
   Guide <https://docs.cumulusnetworks.com/download/attachments/8362527/Cumulus%20Linux%203.7.0%20User%20Guide.pdf?version=4&modificationDate=1537474618000&api=v2>`__
-  `Cumulus Linux 3.6.2 User
   Guide <https://docs.cumulusnetworks.com/download/attachments/8362527/Cumulus%20Linux%203.6.2%20User%20Guide.pdf?version=3&modificationDate=1537474847000&api=v2>`__
-  `Cumulus Linux 3.6.1 User
   Guide <https://docs.cumulusnetworks.com/download/attachments/8362527/Cumulus%20Linux%203.6.1%20User%20Guide.pdf?version=2&modificationDate=1537401092000&api=v2>`__
-  `Cumulus Linux 3.6.0 User
   Guide <https://docs.cumulusnetworks.com/download/attachments/8362527/Cumulus%20Linux%203.6.0%20User%20Guide.pdf?version=1&modificationDate=1537401092000&api=v2>`__
-  `Cumulus Linux 3.5.3 User
   Guide <https://docs.cumulusnetworks.com/download/attachments/8362527/Cumulus%20Linux%203.5.3%20User%20Guide.pdf?version=1&modificationDate=1537401092000&api=v2>`__
-  `Cumulus Linux 3.5.2 User
   Guide <https://docs.cumulusnetworks.com/download/attachments/8362527/Cumulus%20Linux%203.5.2%20User%20Guide.pdf?version=1&modificationDate=1537401092000&api=v2>`__
-  `Cumulus Linux 3.5.1 User
   Guide <https://docs.cumulusnetworks.com/download/attachments/8362527/Cumulus%20Linux%203.5.1%20User%20Guide.pdf?version=2&modificationDate=1537401092000&api=v2>`__
-  `Cumulus Linux 3.4.3 User
   Guide <https://docs.cumulusnetworks.com/download/attachments/8362527/Cumulus%20Linux%203.4.3%20User%20Guide.pdf?version=1&modificationDate=1537401092000&api=v2>`__
-  `Cumulus Linux 3.3.2 User
   Guide <https://docs.cumulusnetworks.com/download/attachments/8362527/Cumulus%20Linux%203.3.2%20User%20Guide.pdf?version=1&modificationDate=1537401092000&api=v2>`__
-  `Cumulus Linux 3.2.1 User
   Guide <https://docs.cumulusnetworks.com/download/attachments/8362527/Cumulus%20Linux%203.2.1%20User%20Guide.pdf?version=1&modificationDate=1537401092000&api=v2>`__
-  `Cumulus Linux 3.1.2 User
   Guide <https://docs.cumulusnetworks.com/download/attachments/8362527/Cumulus%20Linux%203.1.2%20User%20Guide.pdf?version=1&modificationDate=1537401092000&api=v2>`__
-  `Cumulus Linux 3.0.1 User
   Guide <https://docs.cumulusnetworks.com/download/attachments/8362527/Cumulus%20Linux%203.0.1%20User%20Guide.pdf?version=1&modificationDate=1537401092000&api=v2>`__

Contents
========

   .. toctree::
      :maxdepth: 2

      quick-start-guide/index
      system-configuration/network-command-line-utility-nclu/index
      system-configuration/switchd/index
      system-configuration/setting-date-and-time/index
      system-configuration/interface-configuration-and-management/index
