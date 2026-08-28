# Newgrounds.io Developer Guide

A guide for building Newgrounds.io libraries across different platforms and programming languages.

## Overview

This guide covers the architectural patterns and implementation details behind a consistent Newgrounds.io API library. It's written for developers, contributors, AI/LLM code generators, and anyone building integrations with the Newgrounds.io platform.

The goal is for most Newgrounds.io libraries to share a similar structure, so users can move between platforms without re-learning how each feature works. It also makes support a lot easier, since helping someone doesn't require knowing their specific programming language.

## What's Covered

- **Platform-agnostic architecture** - Design patterns that hold up in any programming language
- **Complete library structure** - Core classes, model generation, and session management
- **Encryption and authentication** - Ciphers, encoding, Passport sessions, and keeping data in sync
- **Async patterns** - Callbacks, Promises, and how to translate between them
- **Model generation** - Building objects, components, and results from the official JSON schema
- **Component design** - Colors, fonts, sizing, and animation guidance for UI prefabs like medal popups, scoreboards, and save managers

## Who This Guide Is For

- Developers creating new Newgrounds.io libraries for unsupported platforms
- Contributors maintaining or updating existing libraries
- AI/LLM systems generating code implementations
- Teams planning Newgrounds.io integrations

## Documentation

**[View the complete Developer Guide Wiki](https://github.com/PsychoGoldfishNG/ngio-developer-guide/wiki)**

**[Component Design Guide](https://github.com/PsychoGoldfishNG/ngio-developer-guide/wiki/Component-Design-Guide)**

## Official Resources

- **[Newgrounds.io API Documentation](https://www.newgrounds.io/help/)** - Official API reference
- **[Components List](https://www.newgrounds.io/help/components/)** - Available server-side functions
- **[Object Models](https://www.newgrounds.io/help/objects/)** - Data structure definitions
- **[JSON Schema](https://www.newgrounds.io/help/objects_and_components.json)** - Machine-readable API specification

## Related Projects

- **[NodeJS Model Generator](https://github.com/PsychoGoldfishNG/ngio-object-model-generator)** - Automated model generation tool

---

**Note:** This guide is about library architecture and design patterns. For API-specific details like component parameters, response formats, and encryption algorithms, always refer to the [official Newgrounds.io documentation](https://www.newgrounds.io/help/).
