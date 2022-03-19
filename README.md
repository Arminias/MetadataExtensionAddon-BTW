# MetadataExtensionAddon-BTW

This repository uses the [BTW-gradle-example](https://github.com/BTW-Community/BTW-gradle) repository as the dev
environment.

This addon for BTW introduces additional block metadata capabilities for addon developers by adding 
extra metadata to each block, 32 bits to be precise. These can be accessed using the new extra metadata 
methods, which work exactly like the standard ones, just with 32 bits.


### Considerations
Be aware of the usual Java implications when handling (un-)signed integers. Internally, the extra metadata integers
are handled unsigned, so all 32 bits can actually be used.



