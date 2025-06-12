# OpenLangAI Starter

This repository contains the initial scaffold for the **OpenLangAI** iOS application.

## Generating the Xcode project

1. Install **XcodeGen** if you don't have it:

```bash
brew install xcodegen
```

2. From the repo root, run:

```bash
xcodegen generate
open OpenLangAI.xcodeproj
```

That will create the Xcode project with one iOS app target and four framework targets that wrap the Swift‑package‑style modules.

## What's inside

```
OpenLangAI/
├── project.yml
├── OpenLangAIApp/      # iOS application source
└── Packages/           # Reusable framework modules
```

All modules build for iOS 15+. Feel free to rename the bundle ID prefix in **project.yml** before generating.
