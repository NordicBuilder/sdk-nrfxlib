.. _zboss_changelog:

Changelog
#########

.. contents::
   :local:
   :depth: 2

All notable changes to this project in |NCS| are documented in this file.

nRF Connect SDK v1.5.0
**********************

Added
=====

* Development ZBOSS stack library version based on the ZBOSS build v3.5.0.0.
  This library version is dedicated for :ref:`NCP development <nrf:ug_zigbee_platform_design_ncp_details>`.
* Development libraries for the Cortex-M33 CPU.

Changes
=======

* Updated the production ZBOSS stack to version ``3.3.0.6+11_30_2020``.
  For detailed release notes for this stack version, see `ZBOSS stack release notes`_ for the |NCS| v1.5.0.

nRF Connect SDK v1.4.0
**********************

Added
=====

* Added ZBOSS changelog.

Changes
=======

* Updated ZBOSS stack to version ``10_06_2020``.
  For detailed release notes for this stack version, see `ZBOSS stack release notes`_ for the |NCS| v1.4.0.
* Unified OSIF layer for LEDs and buttons.
* Updated the ZBOSS release naming convention for nrfxlib commit.
* Changed MAC LL API.
* ZBOSS IO buffer size reconfigured to allow for sending 802.15.4 MAC frame with maximum payload.

Limitations
***********

This sections lists limitations that apply to all versions of nRF Connect SDK.

* On average, ZBOSS alarms last longer by 6.4 percent than Zephyr alarms.
