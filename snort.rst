Snort
=====

Snort is a Network Intrusion Detection System (`<NIDS>`_). It sniffs network traffic and generates IDS alerts.

Performance
-----------

In Security Onion, we compile Snort with `<PF-RING>`__ to allow you to spin up multiple instances to handle more traffic.

Configuration
-------------

You can configure Snort via ``/etc/nsm/HOSTNAME-INTERFACE/snort.conf`` (where HOSTNAME is your actual hostname and INTERFACE is your actual sniffing interface).

If you would like to configure/manage IDS rules, please see the `<Rules>`__ and `<ManagingAlerts>`__ sections.

Logging
-------

If you need to troubleshoot Snort, check the Snort log file(s) ``/var/log/nsm/HOSTNAME-INTERFACE/snortu-X.log`` (where ``HOSTNAME`` is your actual hostname, ``INTERFACE`` is your actual sniffing interface, and ``X`` represents the number of PF-RING instances).

More Information
----------------

For more information about Snort, please see https://snort.org.
