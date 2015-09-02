# Pool Automation

An **open source** pool automation system for [Raspberry Pi](https://www.raspberrypi.org).

Current pool automation systems are both costly (running upwards of thousands of US dollars currently) and proprietary, making them accessible to very few pool owners. The charter of this project is to create an open, generic pool controller that anyone can build or hack on.

## Features

This system should be a single-box replacement for your pump timer, solar controller and ultimately SWG controller. Here's my dream feature list:

  * Control variable-speed pumps on any schedule imagineable
  * Monitors one or more temperature probes
  * Control one or more valve actuators to enable solar heating or spa features
  * Provides a well documented REST API for integration with mobile applications or anything else imagineable.
  * Emits data to a time-series database to enable construction of interesting graphs and alerts

## Current Projects

One known related effort is [Poolduino](http://poolduino.com/) which specifies hardware design for a break-out board that handles all the pool automation I/O. It would be a great partner project to this one but it seems to have whithered on the vine.
