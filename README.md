# DynamicExternalObjsAndGroups
Sonicwall dynamic external objects and groups

This is the comprehensive list of IPs and FQDNs that were reported to us as malicious. Use dynamic external objects to import the TAGs into sonicwalls. This list can be upated and the sonicwalls should pick it up periodically.

Make sure the Allow rules for remote access by hiTech are higher priority than the TAG rules.

When creating TAG rules, bock WAN->WAN, ANY->WAN, and WAN->ANY. Use firewalled subnets for the ANY rules.
