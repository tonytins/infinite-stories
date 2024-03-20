# Infinite Stories

<p align="center">
<p>
<p>
<img src="./icon.png" width="350">
</p>
<p>
Infinite Stories is a NovelAI and AI Dungeon frontend.
</p>
</div>

## Background

While web technologies continue to evolve, implementations of the [PWA](https://en.wikipedia.org/wiki/Progressive_web_app) standard remain fragmented to nonexistent, and often leave a lot to be desired. Only Chrome has support for it, but all popular desktop apps are just fancy wrappers around it, anyway. This has made attempting to use something like NovelAI or AI Dungeon as standalone desktop apps rather frustrating, to say the least. While Latitude does offer one on mobile, there is no equivalent on desktop. Infinite Stories is intended to solve this dilemma, but it uses the operating system's native web renderer instead.

## Requirements

### Supported Platforms

| Platform | Versions                           |
| -------- | ---------------------------------- |
| Windows  | 7 or later                         |
| macOS    | 10.15 or later                     |
| Linux    | webkit2gtk 4.1 (e.g. Ubuntu 20.04) |

### Prerequisites

- [Rust](https://www.rust-lang.org/tools/install) 2021 edition
  - [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode)
- [VS Code](https://code.visualstudio.com/)
  - [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

## Getting Started

```shell
$ yarn
$ yarn tauri dev # Or "cargo tauri dev"
```

### Building

```shell
$ yarn tauri build # Or "cargo tauri build"
```

## Disclaimer

This project is not endorsed by or affiliated with NovelAI or AI Dungeon. 
NovelAI and AI Dungeon are copyright to their respective owners.

## License

I license this project under the GPL-3.0 license - see [LICENSE](LICENSE) for details.