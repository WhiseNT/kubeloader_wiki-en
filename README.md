# Main project
project here: https://github.com/WhiseNT/kubeloader

# KubeLoader - Next Generation KubeJS Development Framework

## Overview

**KubeLoader** is not just another KubeJS addon—it's a **future-ready modular development platform** for KubeJS that revolutionizes how scripts are created, distributed, and managed.

**KubeLoader** introduces a revolutionary **ContentPack system** that redefines how KubeJS scripts are distributed and loaded, enabling scripts to be treated as first-class mod citizens.

This document provides an overview of KubeLoader's architecture, core components, and extension mechanisms for the KubeJS framework.

For detailed information about ContentPack structure and creation, please refer to the ContentPack documentation.

## What is KubeLoader?

KubeLoader is the next-generation development framework for KubeJS. It provides a complete modular system—**ContentPacks**—that allows developers to build, integrate, and publish KubeJS functionality in a "mod-like" manner, completely eliminating the flat and coupled nature of traditional scripts.

*Note: ContentPacks are not just script packages; they can simultaneously carry assets and data content, making them a superset of resource packs + data packs.*

With KubeLoader, developers no longer just write scripts—they develop reusable functional modules. You can:

* **Develop scripts like mods**: Enjoy independent dependency management, namespaces, and lifecycle control.
* **Load functionality like installing mods**: Easily integrate ContentPacks developed by others to rapidly build complex projects.
* **Share contentpacks like publishing mods**: Export as .jar files with one click and publish directly to CurseForge or Modrinth as proper mods.

KubeLoader aims to become the **"script operating system"** for the KubeJS ecosystem—managing modules, coordinating dependencies, extending capabilities, and providing a unified development paradigm for the entire community.

With KubeLoader, you can approach script development with a modular mindset and develop/publish ContentPacks with the same rigor as developing mods.

## Core Features

KubeLoader provides a suite of powerful features designed to enhance the KubeJS script development experience:

### 🚀 **ContentPack System**
- **Multi-format Support**: Read ContentPacks from folders, ZIP archives, and JAR files
- **Rapid Development**: Quickly create ContentPack projects and export them as JAR mods
- **Modular Architecture**: Treat scripts as independent, reusable modules

### ⚡ **Enhanced Event System**
- **Extended Events**: Add new Forge events to enhance script development capabilities
- **Advanced Tooling**: Additional utility classes to streamline KubeJS development
- **Lifecycle Management**: Comprehensive control over ContentPack initialization and execution

### 🔗 **Dependency Management**
- **Smart Dependency Resolution**: Automatic sorting and loading of ContentPack dependencies
- **Cross-Pack Communication**: Secure data sharing and communication between ContentPacks via API
- **Version Compatibility**: Robust handling of version requirements and conflicts

### 📦 **Resource Integration**
- **Assets & Data Support**: ContentPacks can include both assets and data resources
- **Automatic Resource Pack Handling**: Seamless integration with Minecraft's resource system
- **Namespace Management**: Proper namespace isolation and conflict prevention

### 🛠️ **Developer Experience**
- **Command Integration**: `/kl pack` and `/kl mod` commands for easy ContentPack management
- **Mixin Support**: Extensive mixin integration for deep Minecraft modification
- **Debugging Tools**: Enhanced logging and error reporting for easier development

