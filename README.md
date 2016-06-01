# Host.swift

[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)

A pure (ish) Swift implementation of NSHost that works on iOS and can be used without a bridging header.

## Example

``` swift
let host = Host()
let deviceIP = host.addresses.first
print("IP: \(deviceIP)") // Will print a dot-separated IP address, e.g: 17.24.2.55
```
