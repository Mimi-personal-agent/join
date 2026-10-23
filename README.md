# join

Planned one-click join portal for Mimi-personal-agent.

## Current status

As reviewed on 2026-10-23, this repository contains only this README.
There is no portal implementation, invitation service, dependency manifest,
local run command, test suite, or deployment configuration in the source tree.
The portal description is a project goal; a working join flow has not been
established by this repository.

## Entry point and next step

This README is currently the only entry point. No working join link or
application entry point is provided here.

Before implementation, define the intended join flow and choose between a
read-only guide and a service that performs invitations. If a service is chosen,
define authorization, failure handling, result confirmation, and rollback before
connecting it to any external system. Add run instructions and test evidence
when an implementation exists; treat production acceptance as a separate step.
