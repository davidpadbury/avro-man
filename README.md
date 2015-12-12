![avro-man](https://cloud.githubusercontent.com/assets/823104/11759997/e25ebb6e-a080-11e5-8465-3e8ccad32e8d.png)

# Native Javascript Avro Implementation

## Background

This code was initially taken from http://code.google.com/p/javascript-avro/, then significantly improved by Ali Bawany.  Since, it's been substantially trimmed, restricted to meet the needs of the X.commerce infrastructure (see below) and converted into a Node.js module.

## Limitations

To optimize for use with the X.commerce platform, the module operates with Avro schemas, not protocols.
