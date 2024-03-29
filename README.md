# Installation


Follow the official [hugo instructions](https://gohugo.io/themes/installing-and-using-themes/)
to install the theme.

Which goes something like this:

```bash
git submodule add https://github.com/izzyhub/aboutme-theme.git themes/aboutme
```

Add this line to your `config.toml` (or change it if you already
have a theme.
```toml
theme = "aboutme"
```

# Configuration

You can add links to the bottom with a `[params]` section in your `config.toml`.
For example:

```toml
[params]
  email = "mail@example.com"
  github = "https://github.com"
  twitter = "twitter_username"
  linkedin = "https://www.linkedin.com"
  mastadon = "https://mastadon.social/@username"
```

Mastadon links use "rel=me" for mastadon verification.

You can also add your location
```toml
[params]
  location = "Roswell, NM"
```

Change the page title with
```toml
[params]
  title="About Me"
```

# Content
Create a `content/_index.md` file to hold the content of your page.
The page's main header and title are in the title variable.
```yaml
title: "Page title"
```

The rest of the file is markdown.

# Credits
This theme uses [Font Awesome](https://fontawesome.com/) for the SVG icons.
