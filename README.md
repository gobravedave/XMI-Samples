# Objectives

The goal of this project if to document XMI format used by *Sparx Enterprise Architect*.
We will first focus on sequence diagrams.

To start, we are going to create some very basic sequence diagrams with EA and save them to XMI format. We will then manually edit those XMI file to understand the meaning of used tags there.

## Current results

| Filename | Details | Result | Conclusion |
| -------- | ------- | ------ | ---------- | 
| *EA3.xml* | Working example with only one message | Working | 
| *EA31.xml* | *EA3.xml* with suppression of `<times>` and modification of `<xmi:Documentation>` | Not working | Hard to say, probably `<xmi:Documentation>` should not be modified. Testing *EA32.xml* will tell us |
| *EA32.xml* | *EA3.xml* with suppression of `<times>` | Pending | Pending |
| *EA5.xml* | *EA3.xml* with suppression of `<times>` and modification of `<xmi:Documentation>` and `<constraints/>` `<documentation/>` `<xrefs/>` `<tags/>` `<code>` `<times>` | Not working | Hard to say until we fix *EA31.xml* |
