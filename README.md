# Natsume

Natsume is a single-column [hugo](http://hugo.spf13.com) theme. It tries to be very simple, clean.

![Natsume screenshot](https://f.cloud.github.com/assets/98681/1831228/42af6c6a-7384-11e3-98fb-e0b923ee0468.png)


## Contents

- [Options](#options)
  - [Hero image per post](#hero-image)
  - [Disqus](#disqus)
  - [Goole Analytic](#disqus)
- [Author](#author)
- [License](#license)


## Options

Natsume includes some customizable options, typically applied via front mattern or config file.

### Hero image

Natsume has a dedicated hero image for each post. Simply create a new field
`background_image` in meta section of post.

```toml
+++
date = "2015-08-07T15:12:54-07:00"
draft = false
title = "How I setup this blog"
description = "Let's start with hugo"
author = "Vinh"
background_image="/images/setup.jpg"
+++
```

### Post author

Natsume will show who writes the post by reading an `author` fields.

```toml
+++
date = "2015-08-07T15:12:54-07:00"
draft = false
title = "How I setup this blog"
description = "Let's start with hugo"
author = "Vinh"
background_image="/images/setup.jpg"
+++
```

### Disqus

You can optionally enable a comment system powered by Disqus for the posts. Simply add the variable `disqusShortname` to the `params` in your config file.

**TOML**
```toml
[params]
  disqusShortname = "kureikain"
```

**YAML**
```yaml
params:
  disqusShortname: "kureikain"
```

## Author
**Vinh Nguyen**
- <https://github.com/kureikain>
- <https://twitter.com/kureikain>

## License

Open sourced under the [MIT license](LICENSE.md).

<3
