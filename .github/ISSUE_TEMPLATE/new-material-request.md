---
name: New Material Request
description: Recommend a reading material about dotnet or C#
title: '[Link]: '
assignees:
  - sinannar
body:
  - type: dropdown
    id: type
    attributes:
      label: Type of reading material
      options:
        - C#
        - Dotnet/Aspnet
        - Sofware Engineering
        - Tooling
  - type: dropdown
    id: level
    attributes:
      label: Level of reading material
      options:
        - Beginner
        - Intermediate
        - Senior
  - type: input
    id: description
    attributes:
      label: What is this material about
      description: Give some details
  - type: input
    id: hyperlink
    attributes:
      label: Public accessible URL of the material
      description: Public URL
---


