name: Bug Report
description: Create a bug report
title: "[bug]: "
labels: ["bug"]
body:
  - type: markdown
    attributes:
      value: |
        Please provide as much information as you can in this bug report!
        Also remember to provide a reproducer if possible, it will make it easier and quicker to help you 😉
  - type: textarea
    id: what-issue
    attributes:
      label: What is the issue?
      description: Please provide all the steps that lead to your issue, the relevant information (logs, screenshots, versions, ...) and also what did you expect to happen!
      value: |
        * The steps that lead to the issue:
          
          ...
          
        * The expected behavior:
          
          ...
          
        * The reproducer you can use:
          
          ...
          
    validations:
      required: true
  - type: textarea
    id: proposal-solution
    attributes:
      label: Proposal solution?
      placeholder: Did you find any solution?
      value: |
        * The solution I have found to solve the issue:
          
          ...
          