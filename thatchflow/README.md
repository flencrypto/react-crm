# ThatchFlow Pro Android SDK

This folder contains the modular Android SDK project built with Kotlin and Jetpack Compose.
Each subfolder under `modules` represents a feature module that can be enabled or disabled
when embedding the SDK in the main application.

```
modules/
  core/               # Shared utilities, authentication, networking
  projectManagement/  # Gantt and Kanban boards, job diary
  staffScheduling/    # Staff profiles, scheduling, GPS time logging
  timesheets/         # Clock in/out and wage calculations
  quoteBuilder/       # Quote creation wizard with AI features
  photos/             # Photo capture, document scanning
  crm/                # Client relationship management
  clientPortal/       # Client portal integration
  aiForeman/          # AI assistant and recommendations
```

Additional Android build configuration files should reside in this directory.
