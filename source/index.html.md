---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - json
  - yml

toc_footers:
  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---

# Introduction

Welcome to "documenting configuration by abusing API documentation" with @agc93.

This way, you can explain config keys and their meaning/effects/options on the left, and show a reasonably easy sample on the right. Added bonus for .NET Core projects: you can abuse the multi-language features (top-right I think) to handle multiple config formats.

This example API documentation page was created with [Slate](https://github.com/lord/slate). Feel free to edit it and use it as a base for your own API's documentation.

# Base URLs

> Set your base URL first:

```json
{
  "baseURL": "https://wow-this-is-hacky.ihavenoshame.com/"
}
```

```yaml
- baseUrl: "https://wow-this-is-hacky.ihavenoshame.com/"
```

> Make sure to replace the sample domain with your own.

This way, you get all the power of ***markdown*** to write your config samples while still getting to see the `code` for configuration on the right.

<aside class="notice">
Slate in particular has some neat extra HTML trickery
</aside>

# Other Configuration Options

## Faith In Humanity

```json
{
  "humanity": {
    "faith": 0
  }
}
```

```yaml
humanity:
  - faith: 0
```

> The above command returns JSON structured like this:

```json
[
  {
    "result": "Admittedly this part isn't so applicable to docs"
  }
]
```

This endpoint indicates how much faith in your users has been eroded by unbelievably poor security practices.
