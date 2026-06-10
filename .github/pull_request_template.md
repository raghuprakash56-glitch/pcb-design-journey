---
name: Pull Request
description: Submit a pull request to improve the PCB Design Journey
title: '[FEATURE/FIX] Brief description of changes'
labels: ['review-needed']

body:
  - type: markdown
    attributes:
      value: |
        Thanks for contributing to PCB Design Journey! Please provide details about your pull request.

  - type: textarea
    id: description
    attributes:
      label: Description
      description: Explain what changes you've made and why
      placeholder: |
        Describe your changes in detail...
    validations:
      required: true

  - type: checkboxes
    id: type
    attributes:
      label: Type of Change
      description: What type of contribution is this?
      options:
        - label: Documentation update
        - label: New example project
        - label: Bug fix
        - label: Enhancement
        - label: Schematic/Layout addition
        - label: Tool guide or tutorial

  - type: textarea
    id: related-issues
    attributes:
      label: Related Issues
      description: Link any related issues (e.g., Closes #123)
      placeholder: |
        Closes #
        Related to #

  - type: textarea
    id: testing
    attributes:
      label: Testing
      description: How have you tested these changes?
      placeholder: |
        Describe how you validated your changes...

  - type: checkboxes
    id: checklist
    attributes:
      label: Checklist
      description: Ensure you've completed these items
      options:
        - label: My changes follow the project structure and naming conventions
        - label: I've updated documentation where needed
        - label: I've tested my changes thoroughly
        - label: I've cited sources and references where applicable
        - label: I've reviewed the Contributing guidelines
          required: true

  - type: textarea
    id: additional-context
    attributes:
      label: Additional Context
      description: Any other information that might be helpful
      placeholder: Add screenshots, links, or other relevant information...