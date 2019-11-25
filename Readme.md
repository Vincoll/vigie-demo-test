# Vigie Tests Demo

This repo contains examples of Tests used by [Vigie](https://vigie.dev) to performs tests and assertions.

## Goals

* Tests contained in this repo are used in the demo of [Vigie](https://vigie.dev).
  * Go check [vigie.dev/demo](https://vigie.dev/demo)

* Provide tests examples for all the Vigie's built-in probes

## Structure

### **`./test/`**

Contains TestSuites files.

### **`./var/`**

Contains files containing variables used by TestSuites.

### **`./vigieconf.toml`**

Is an example of a Vigie config file.
Section `git` of this example being completed, it allows Vigie to clone this repo.
