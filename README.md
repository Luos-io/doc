<a href="https://luos.io"><img src="https://uploads-ssl.webflow.com/601a78a2b5d030260a40b7ad/602f8d74abdf72db7f5e3ed9_Luos_Logo_animation_Black.gif" alt="Luos logo" title="Luos" align="right" height="60" /></a>

![](https://github.com/Luos-io/Luos/workflows/Build/badge.svg)
[![](http://certified.luos.io)](https://luos.io)
[![](https://img.shields.io/github/license/Luos-io/Luos)](https://github.com/Luos-io/Luos/blob/master/LICENSE)
[![](https://img.shields.io/reddit/subreddit-subscribers/Luos?style=social)](https://www.reddit.com/r/Luos)
[![](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Unleash%20electronic%20devices%20as%20microservices%20thanks%20to%20Luos&https://luos.io&via=Luos_io&hashtags=embeddedsystems,electronics,microservices,api)
[![](https://img.shields.io/badge/LinkedIn-Share-0077B5?style=social&logo=linkedin)](https://www.linkedin.com/sharing/share-offsite/?url=https%3A%2F%2Fgithub.com%2Fluos-io)

# What and why Luos? :bulb:

We started designing Luos with the conviction that building electronic systems should be made easier than it is today. Most of the time should be spent on designing the applications and behaviors instead of on complex and time-and-money-eating technicalities. To give a simple example, adding a new sensor —for instance a distance sensor— to an electronic device in conception should not take more than a few minutes. So you can try, test and iterate fast on a project to truly design what users want.

Luos works like [microservices architecture](https://en.wikipedia.org/wiki/Microservices) in the software world, and a [distributed operating systems](https://en.wikipedia.org/wiki/Distributed_operating_system): it encapsulates any software or hardware function to make it communicate and work with any other encapsulated module, however it was developed, either on bare metal or on top of an embedded OS.

Watch this video for additional details:

<a href="https://youtu.be/xQe3z0M_FE8"><img border="0" alt="Luos video" src="https://uploads-ssl.webflow.com/601a78a2b5d030260a40b7ad/6035128c3e63c132f1743d13_youtube.jpeg" width="640" height="360"></a>

## You are not familiar with Luos operations?

→ Start reading the [Basics](https://docs.luos.io/pages/overview/general-basics.html) page.

## You want to make your own board with [Luos modules](https://docs.luos.io/pages/low/modules/create-modules.html)?

→ Start reading how to integrate Luos in you [Development environment](https://docs.luos.io/pages/low/dev-env.html).

→ Then learn how to [Create a luos project](https://docs.luos.io/pages/low/modules/create-project.html).

## You want to shape your device behavior?

→ Luos provides a sets of [Prototyping boards](https://docs.luos.io/pages/prototyping_boards/boards-list.html) you can use as example or to develop your project.

→ You can make your own embedded [Luos apps](https://docs.luos.io/pages/low/modules/create-modules.html).

→ You can control your devices through a [Gate](https://docs.luos.io/pages/high/modules_list/gate.html) module using [Pyluos](https://docs.luos.io/pages/high/pyluos.html).

If you have questions about a specific topic, you can refer or ask it on the [Luos' Forum](https://community.luos.io/). And if you have suggestions about this documentation don't hesitate to create pull requests.

## mdBook
We use the static page generator mdBook for this documentation.
To use and visualize it locally:

 - Download and install [Rust](https://www.rust-lang.org/) (at least 1.35) and Cargo
 - Download and install [Visual Studio C++ Community](https://visualstudio.microsoft.com/fr/vs/features/cplusplus/)
 - Update rust: `rustup update`
 - Install mdBook: `cargo install mdbook`
 - Install various preprocessors for mdBook: `cargo install -f mdbook-variables` and `cargo install mdbook-linkcheck`
 - In the documentation folder, run `mdbook serve`. You will be able to see local changes at `http://localhost:3000`

More information: <a href="https://rust-lang.github.io/mdBook/index.html" target="_blank">Official mdBook documentation</a>

## Don't hesitate to read [our documentation](https://docs.luos.io), or to post your questions/issues on the [Luos' subreddit](https://www.reddit.com/r/Luos/). :books:

[![](https://img.shields.io/reddit/subreddit-subscribers/Luos?style=social)](https://www.reddit.com/r/Luos)
[![](https://img.shields.io/badge/Luos-Documentation-34A3B4)](https://docs.luos.io)
[![](https://img.shields.io/badge/LinkedIn-Follow%20us-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/company/luos)
