# &lt;bandcamp-player&gt;

[Web Component](http://www.w3.org/TR/components-intro/) wrapper component for Bandcamp embedded player [Polymer](http://www.polymer-project.org/).

## [Demo](http://codepen.io/anon/pen/wappgx)

## Usage

1. Install from bower:

  ```
  bower install polymer-embed-bandcamp
  ```

2. Import Custom Element:

  ```html
  <link rel="import" href="bandcamp-player.html">
  ```

3. Start using it!

  ```html
  <bandcamp-player albumid="2263483982" size="large" bgcolor="000000" linkcolor="0687f5"=></bandcamp-player>
  ```

## Options

Attribute      | Default  | Description
---            | ---      | ---
`albumid`      | None     | The ID of the Bandcamp album
`size`         | None     | "small" or "large"
`bgcolor`      | None     | The HEX color of the player background
`linkcolor`    | None     | The HEX color of the player album link
