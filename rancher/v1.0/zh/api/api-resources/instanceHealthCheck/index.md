---
title: API
layout: rancher-default-v1.0
version: v1.0
lang: zh
---

## instanceHealthCheck





### Resource Fields

Field | Type | Required | Default | Description
---|---|---|---|---
healthyThreshold | int | false |  | 
initializingTimeout | int | false |  | 
interval | int | false |  | 
name | string | false |  | 
port | int | true |  | 
recreateOnQuorumStrategyConfig | [recreateOnQuorumStrategyConfig]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/recreateOnQuorumStrategyConfig/) | false |  | 
reinitializingTimeout | int | false |  | 
requestLine | string | false |  | 
responseTimeout | int | false |  | 
strategy | enum | false | recreate | 
unhealthyThreshold | int | false |  | 

