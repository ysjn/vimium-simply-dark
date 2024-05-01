# vimium-simply-dark

Dark theme for [vimium chrome extension](https://github.com/philc/vimium).

### Screenshots

#### <kbd>f</kbd> Open links

<img src="https://raw.githubusercontent.com/ysjn/vimium-simply-dark/master/captures/openLink.png" width="725" />
<img src="https://raw.githubusercontent.com/ysjn/vimium-simply-dark/master/captures/openLink2.png" width="725" />

#### <kbd>o</kbd> Vomnibar

<img src="https://raw.githubusercontent.com/ysjn/vimium-simply-dark/master/captures/find.png" width="725" />

#### <kbd>/</kbd> Find

<img src="https://raw.githubusercontent.com/ysjn/vimium-simply-dark/master/captures/vomnibar.png" width="725" />

### Installation

Copy and paste the [vimium-simply-dark.css](https://github.com/ysjn/vimium-simply-dark/blob/master/vimium-simply-dark.css) in Vimium settings.

<img src="https://raw.githubusercontent.com/ysjn/vimium-simply-dark/master/captures/installation.png" width="725" />

### Customization

You can customize colors based on your preference by changing variables specified under `/** Customizable Palette */`.

#### Sample - Changing the accent color

```css
:root {
  /** Customizable Palette */
  --accent: yellow;
  --text: #fff;
  --background: #444;
```

<img src="https://raw.githubusercontent.com/ysjn/vimium-simply-dark/master/captures/customize_accent.png" width="725" />

#### Sample - Making it darker

```css
:root {
  /** Customizable Palette */
  --accent: hotpink;
  --text: #fff;
  --background: #111;
```

<img src="https://raw.githubusercontent.com/ysjn/vimium-simply-dark/master/captures/customize_darken.png" width="725" />

#### Sample - Transparency

```css
:root {
  /** Customizable Palette */
  --accent: hotpink;
  --text: #fff;
  --background: rgb(30 30 30 / 90%);
```

<img src="https://raw.githubusercontent.com/ysjn/vimium-simply-dark/master/captures/customize_transparency.png" width="725" />

#### Sample - Fancy

```css
:root {
  /** Customizable Palette */
  --accent: mediumorchid;
  --text: blue;
  --background: pink;
```

<img src="https://raw.githubusercontent.com/ysjn/vimium-simply-dark/master/captures/customize_fancy.png" width="725" />
