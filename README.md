How to use me
=============

This script has mainly be designed to be running on SLES 12 or openSUSE 13+
either from a Jenkins CI instance or manually.

 * Setup a host with the installed libvirt to test. There are autoyast profiles to
   help this step.
 * Run the test-lxc script
 * Check the results

**Warning:** These tests may include tests for features that aren't pushed in upstream
libvirt yet.
