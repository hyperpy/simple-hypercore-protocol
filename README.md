# simple-hypercore-protocol

[![Build Status](https://drone.autonomic.zone/api/badges/hyperpy/simple-hypercore-protocol/status.svg)](https://drone.autonomic.zone/hyperpy/simple-hypercore-protocol)

## The Hypercore protocol state machine

> **Work In Progress**

## Install

```sh
$ pip install simple-hypercore-protocol
```

## Example

```python
from simple_hypercore_protocol import messages

print(messages.Request(index=0))
```

Output:

```sh
index: 0
```
