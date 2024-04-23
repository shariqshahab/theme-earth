#Earth

The default theme for Halo 2.0.

![Earth](./screenshot.jpg)

## Usage

1. Manually download the theme package from the following address and install it in the theme management interface of the Console. For the installation method, please refer to: <https://docs.halo.run/user-guide/themes>

    - https://www.halo.run/store/apps/app-KgWqR
    - https://github.com/halo-dev/theme-earth/releases

3. If you have installed the [App Market](https://www.halo.run/store/apps/app-VYJbF) plug-in, you can directly search for `Earth` in the App Market and install it.

## Plug-in support

The Earth theme supports the following Halo plugins:

- Friendly links (/links): <https://halo.run/store/apps/app-hfbQg>
- Gallery (/photos): <https://halo.run/store/apps/app-BmQJW>
- Moments (/moments): <https://halo.run/store/apps/app-SnwWD>

For a better experience, you can also install the following plugins (if needed):

- highlight.js code highlighting: <https://halo.run/store/apps/app-sqpgf>
- lightgallery.js lightbox: <https://halo.run/store/apps/app-OoggD>

## Development

```bash
git clone git@github.com:halo-dev/theme-earth.git ~/halo2-dev/themes/theme-earth
```

```bash
cd ~/halo2-dev/themes/theme-earth
```

```bash
pnpm install
```

```bash
pnpmdev
```

Theme development documentation can be found at: <https://docs.halo.run/2.0.0-SNAPSHOT/developer-guide/theme/prepare>

## Construct

> If you are using a Windows operating system, please install the `make` command and execute it in Git Bash or WSL.

```bash
make build
```

Then compress the `dist` directory into a `ZIP` format compressed package, which can be uploaded and installed in the Halo background.
