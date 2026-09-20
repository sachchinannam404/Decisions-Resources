---
title: "Compliance Checker Overview"
slug: "compliance-checker-overview"
updated: 2023-12-05T20:27:54Z
published: 2024-05-22T13:59:16Z
canonical: "documentation.decisions.com/compliance-checker-overview"
---

> ## Documentation Index
> Fetch the complete documentation index at: https://documentation.decisions.com/llms.txt
> Use this file to discover all available pages before exploring further.

# Compliance Checker Overview

## Overview

The **Compliance Checker** assesses if process executions are compliant to the specified compliance guidelines. Identifying violations of compliance guidelines early prevents risks and unnecessary costs.

Compliance assessment can be performed on both BPMN models and event logs. Supported comparisons are between two BPMN models, two event logs, or between a BPMN model and an event log. That being said, two events logs and/or BPMN models are required to use the Compliance Checker. To access the Compliance Checker, open an event log and open a new tab by selecting the plus icon at the bottom of the screen. From there, select the Compliance Checker.

Two methods of compliance checking are available and can be toggled above the graph:

- **Control-Flow Compliance (default):** compares and contrasts instance behavior by visualizing variants with a BPMN model
- **Constraints Compliance:** controls instance's event log with constraint rule logic

![](https://cdn.document360.io/6ef8bcc1-6489-4486-9ad1-83acff7e5df0/Images/Documentation/image-1644353731502.png)
