---
name: Update to Dict
about: Create a report to help us improve
title: 'Terminology Update - '
labels: 'dict.txt'
assignees: ''
body:
  - type: markdown
    attributes:
      value: "Intro text"
  - type: dropdown
    id: download
    attributes:
      label: How did you download the software?
      options:
        - Built from source
        - Homebrew
        - MacPorts
        - apt-get
      default: 0
    validations:
      required: true
    
---
