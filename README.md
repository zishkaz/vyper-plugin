### Vyper IntelliJ Plugin

#### Overview

The Vyper IntelliJ Plugin enhances your development experience when working with Vyper smart contracts programming language on the IntelliJ Platform. It offers a range of features to streamline your workflow.

#### Features:

- **Syntax Assistance:** The plugin provides syntax assistance based on the specified language grammar, facilitating navigation, code completion, and syntax highlighting.

- **Development Tools Integration:**
    - *Vyper Compiler:* Compile your Vyper smart contracts seamlessly.
    - *SmartCheck Static Analyzer:* Leverage static analysis for improved code quality.
    - *MythX Integration:* Benefit from MythX with projections onto the editor for enhanced security analysis.

- **Fast Function Testing:** Utilize Vyper-debug/Vyper-run for quick and efficient function testing.

- **Docker Integration:** The plugin seamlessly integrates with Docker, requiring only IntelliJ IDEA and Docker for a smooth development experience.

- **Pre-Alpha:** Please note that the plugin is currently in the pre-alpha stage, and feedback is appreciated.

#### Demo

Explore a demo of the plugin on [YouTube](https://www.youtube.com/watch?v=M6f6xgcP4Xo&feature=youtu.be).

#### Installation

You can download the Vyper IntelliJ Plugin from the official JetBrains Marketplace using the following link: [Vyper Plugin on JetBrains Marketplace](https://plugins.jetbrains.com/plugin/19039-vyper).

#### Build

To build the plugin:

1. Ensure you have IntelliJ IDEA installed.
2. Clone the project.
3. Set your IntelliJ IDEA version in the `build.gradle` file (line `20`).
4. Run the `gradle buildPlugin` task.
5. Locate the created `.zip` file in the `/build/distributions` folder.
6. Install the plugin in IntelliJ IDEA by selecting "Install Plugin from Disk..." and choosing the `.zip` file.

#### Testing

You can test the plugin without installation by running the `runIde` task in Gradle. This will launch an IntelliJ IDEA instance with the plugin installed.

We welcome your feedback and contributions to enhance the Vyper IntelliJ Plugin. Thank you for using our plugin!