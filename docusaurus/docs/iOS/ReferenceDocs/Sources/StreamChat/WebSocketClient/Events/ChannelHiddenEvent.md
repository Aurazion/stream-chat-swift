---
id: channelhiddenevent 
title: ChannelHiddenEvent
slug: referencedocs/sources/streamchat/websocketclient/events/channelhiddenevent
---

``` swift
public struct ChannelHiddenEvent: ChannelSpecificEvent 
```

## Inheritance

[`ChannelSpecificEvent`](ChannelSpecificEvent)

## Properties

### `cid`

``` swift
public let cid: ChannelId
```

### `hiddenAt`

``` swift
public let hiddenAt: Date
```

### `isHistoryCleared`

``` swift
public let isHistoryCleared: Bool
```