# speedport-w724v-external-ip-address
A utility application to determine the external (public) IPv4 address of the
router SpeedPort W724V.

Before using the application, please set the router access password in the
configuration file:
	/etc/speedport_w724v/device_password.conf

This utility can be used with a periodic agent to update your domain name to
point to your current external IP address, even when this address changes.
It is better to use than querying an external Web site, for privacy and
dependability reasons.

The router SpeedPort W724V is commonly distributed by T-Mobile Germany for DSL
Internet contracts (as of 2015).
