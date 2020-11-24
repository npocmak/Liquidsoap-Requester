Liquidsoap Requester -- PHP web app to control your Liquidsoap Audio Stream Generator

based on - https://github.com/QuinnEbert/Liquidsoap-Requester

Requirements:

 * PHP of version 5 or later (PHP v4 not supported)
 * Liquidsoap Audio Stream Generator (for now version 0.9 is "certified" to run, 1.0 will start up, but see below notes).
 * Apache, nginx, lighttpd, litespeed or thttpd web server.

Notes about Liquidsoap 1.0:

 * On 6th October 2020, I tested the example script with Liquidsoap 1.0.1, as provided by Debian 7's default repositories.  The script seemed to start appropriately, queueing of tracks worked, but I was less than impressed with the reliability of playback order--I will be looking into this.

