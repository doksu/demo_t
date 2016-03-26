# demo_t

I've devised this horrible demo "service" to demonstrate how SELinux can successfully confine and therefore protect your system from even the most vulnerable and worst written software, even when run as root. The service is a simple bash shell script that does many of the normal sorts of things services do, but has been designed much like rshell, so arbitrary remote unauthenticated commands can be executed.

N.B. This is still **very much** a work in progress and should **NEVER** be run on any system you care anything about...
