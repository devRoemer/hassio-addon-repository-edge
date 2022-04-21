# Changelog since v1.0.2
- * Improve logging 
- * Improve logging 
- * Run pre script with correct user 
- * Fix Shellcheck warnings 
- * Possibility to run homegear as specific user 
- Revert "* Test ingress support in new version of homegear"

This reverts commit a671ce46f2af4c70068ad7f1a254662de9c1b936. 
- * Improve script syntax to pass shellcheck 
- * Test ingress support in new version of homegear 
- * Add logging for better troubleshooting 
- Update README.md 
- Update README.md 
- * Remove support for i386 because the homegear apt repo does not contain packages for it anymore 
- * Remove support for i386 because the homegear apt repo does not contain packages for it anymore 
- * Change shell and add pipefail for proper error handling 
- * Fix warning: apt-key is deprecated. Manage keyring files in trusted.gpg.d instead 
- * Fix hassio linting error: 'devices' uses a deprecated format, the new format uses a list of paths only. 
- * Add spidev permissions (just to be on the safe side) 
- * Update debian buster (10) to bullseye (11) 
- * Ensure that the checkout still works after repo changes (https://forum.homegear.eu/t/apthomegeareuraspbian-existiert-nicht/4156) 
- * Experimental spi support 
