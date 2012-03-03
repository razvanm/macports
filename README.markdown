Install steps
-------------

1. `cd /User/user`<br />`git clone git://github.com/razvanm/macports.git`
2. Edit `/opt/local/etc/macports/sources.conf` to include a line: file:///Users/user/macports
3. `sudo port install msp430-binutils-tinyos msp430-gcc-tinyos msp430-libc-tinyos` _(for MSP430)_
4. `sudo port install avr-binutils-tinyos avr-gcc-tinyos avr-libc-tinyos avrdude-tinyos` _(for AVR)_

**Note:** nesc 1.3 is already in the latest macports so it can be installed by doing `sudo port install nesc`.

**Changelog:**

* Sep 26, 2011: add nesc 1.3.3.
* Jul 31, 2010: add nesc 1.3.2 rc.
* Dec 2, 2009: add the mcport for avrdude-tinyos. This is used by IRIS.
* Sep 18, 2009: add the macport for nesc 1.3.1 and fix the binutils for MSP430 and AVR for Snow Leopard. The GCC for AVR does not compile properly yet.
* Dec 29, 2008: add the ports for AVR binutils, gcc and libc. Small tweaks for MSP430.
* Dec 28, 2008: add the ports for MSP430 binutils, gcc and libc.
