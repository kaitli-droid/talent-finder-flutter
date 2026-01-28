# Talent Finder

On-demand skilled services marketplace built with Flutter.

## Overview

Talent Finder connects users with nearby skilled workers such as plumbers, electricians, technicians and other casual workers. The platform supports real-time service requests, location-based matching, and structured task workflows from booking to completion.

This repository contains the mobile application.

## Key Focus Areas

- Location-based matching and discovery
- Real-time service request flows
- Booking, task tracking, and status updates
- Reliable networking under poor connectivity
- Clear and predictable user flows

## Tech Stack

- Flutter (Dart)
- Location services
- REST APIs
- Real-time communication services

## Architecture Notes

The app is designed around explicit state transitions for service requests to avoid ambiguous or conflicting states. Network failures and retries are handled deliberately to prevent data inconsistencies and poor user experience.

## Status

Production-ready
(Some services and keys omitted)

## Notes

The focus of this project is reliability in real-world usage, where connectivity and device quality cannot be assumed.
