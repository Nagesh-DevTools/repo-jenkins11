# my-shared-actions/say-hello/action.yml
name: 'Say Hello'
description: 'Greets someone'
inputs:
  name:
    description: 'Who to greet'
    required: true
    default: 'World'
runs:
  using: "composite"
  steps:
    - shell: bash
      run: echo "Hello, ${{ inputs.name }}! This is coming from a GitHub Action."
