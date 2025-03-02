# WinwKit

<img align="right" width="150px" src="https://raw.githubusercontent.com/metafunc/winwkit/refs/heads/main/docs/assets/images/winwkit.png" />

**W**inwKit **I**s **N**ot **W**ebView, it provides a powerful cross-platform development solution with consistency, high performance and portability.

- 🤯 **Cross-Platform.** Powerful cross-platform by implementing wasm first and then runtime
- 🚀 **High-Performance.** Implemented with wasm on rust and native code, the speed is impeccable.
- ♻️ **Consistency.** A variety of well-known standards and built-in tools make it easy to unify even when calling native code.
- 🤓 **So-Easy.** Rich documentation and user-friendly implementation for rapid development.
## 📚 Documentation
- Get started.
- Low-level develop.
- Native/Plugin develop.

## ⬆️ Upgrading
In most cases, all you need to do is download the compilations from the following libraries and place them in `your_project/plugins` folder.

- Components Zero Engine
- Components One Engine
- ByteScript Core

Review this document if framework or tool updates are involved.

## ✏️ Design
![MindMap](https://raw.githubusercontent.com/metafunc/winwkit/refs/heads/main/docs/assets/images/implementation-mindmap.png)

We have some interesting designs to ensure the performance, compactness, and convenience of the project.

- `UniRPC` Ability to implement fast native function calls in the same way as deploying rpc.
- `Wasm and Web APIs` Ensures consistent access to running architecture and methods on any device.
- `ByteScript` Designed a binary format for javascript that breaks away from the problems of character form.
- etc.
