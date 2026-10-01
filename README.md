# Brave Selinux
Experimental Policy For Brave-origin. The purpose of this policy is to protect against xdg-dbus-based, fingerprinting, attacks.
this policy does not have audio by default, can not download files, or even use the gpu , or even access cpu information.

For high threat users. This policy allows the disable_execmem boolean to be enabled while preserving executable memory at the browser level context.
