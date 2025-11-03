# Issue: Request for Comprehensive AudioShare Tutorial

## Summary
Prepare a detailed, step-by-step tutorial that guides new users through installing, configuring, and using AudioShare to share system audio via a virtual microphone.

## Motivation
Newcomers to Linux audio routing often find the process intimidating. A curated tutorial will reduce onboarding friction, highlight best practices, and make it easier to troubleshoot common pitfalls.

## Proposed Content Outline
- **Prerequisites**: Operating system requirements, verifying PipeWire or pipewire-pulse availability, and necessary permissions.
- **Installation**: Cloning the repository, reviewing provided scripts, and outlining optional dependencies.
- **Configuration**:
  - Identifying the relevant sink and source devices.
  - Running the appropriate PipeWire or pipewire-pulse scripts.
  - Understanding how the virtual devices appear in tools like Helvum or `pw-cli`.
- **Usage**: Selecting the "my-mic" virtual microphone in common conferencing applications and managing volume controls independently.
- **Troubleshooting**: Frequent misconfigurations, verifying links, and reverting to defaults.
- **Advanced Tips**: Automating the toggle script with keyboard shortcuts and documenting how to customize device names.

## Acceptance Criteria
- Tutorial lives in the repository documentation (e.g., README section or dedicated markdown file) with clear navigation.
- Includes annotated screenshots or diagrams demonstrating the audio graph after setup.
- Provides commands and configuration snippets that users can copy/paste.
- Reviewed for accuracy on both native PipeWire setups and pipewire-pulse compatibility layers.

## Additional Notes
- Coordinate with maintainers to gather existing troubleshooting knowledge from community feedback.
- Consider cross-linking to the toggle script and any upcoming localization efforts.
