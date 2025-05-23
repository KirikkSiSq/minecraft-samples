---
page_type: sample
author: mammerla
description: A basic example of a set of starter blocks for use within Minecraft.
ms.author: mikeam@microsoft.com
ms.date: 01/31/2024
products:
  - minecraft
---

# Minecraft Starter Block Project

This sample demonstrates some starter custom block types you can use within Minecraft,
and start your own builds and customizations from.

## Prerequisites

**Install Node.js tools, if you haven't already**

We're going to use the package manager [npm](https://www.npmjs.com/package/npm) to get more tools to make the process of building our project easier.

Visit [https://nodejs.org/](https://nodejs.org).

Download the version with "LTS" next to the number and install it. (LTS stands for Long Term Support, if you're curious.) In the Node.js Windows installer, accept the installation defaults. You do not need to install any additional tools for Native compilation.

**Install Visual Studio Code, if you haven't already**

Visit the [Visual Studio Code website](https://code.visualstudio.com) and install Visual Studio Code.

## Getting Started

1. To make your own environment look like the example, create a folder on your `C:\` drive and call it **projects**. Create a subfolder called **starter_blocks**.

1. Put the extracted contents of the starter_blocks folder into **starter_blocks**.

1. Open a Windows Terminal or PowerShell window and change the working directory to your **starter_blocks** folder:

   ```powershell
   cd c:\projects\starter_blocks\
   ```

1. Use npm to install our tools:

   ```powershell
   npm i
   ```

1. When that's done, enter:

   ```powershell
   npm run local-deploy
   ```

1. Use this shortcut command to open the project in Visual Studio Code:

   ```powershell
   code .
   ```

It might also ask you to install the Minecraft Debugger and Blockception's Visual Studio Code plugin, which are plugins to Visual Studio Code that can help with Minecraft development. Go ahead and do that, if you haven't already.

### Summary

This sample demonstrates how you can build incrementally more sophisticated blocks, and how you can leverage custom block features and components.

## Manifest

- [behavior_packs/starter_blocks](https://github.com/microsoft/minecraft-samples/blob/main/starter_blocks/behavior_packs/starter_blocks): This contains behavior implementations for a set of custom blocks.
- [resource_packs/starter_blocks](https://github.com/microsoft/minecraft-samples/blob/main/starter_blocks/resource_packs/starter_blocks): This contains resources for a set of custom blocks.
