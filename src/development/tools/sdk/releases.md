---
title: Flutter SDK releases
short-title: Releases
description: All current Flutter SDK releases, both stable, dev, and master.
toc: false
js:
  - url: /assets/js/archive.js
---

<style>
.scrollable-table {
  overflow-y: scroll;
  max-height: 20rem;
}
</style>

The {{site.sdk.channel | capitalize }} channel contains the
most stable Flutter builds. See [Flutter’s channels][] for details.

**Please note - dev channel has been deprecated. Refer to this [blog](https://medium.com/flutter/whats-new-in-flutter-2-8-d085b763d181) for more information.**

{% comment %} Nav tabs {% endcomment -%}
<ul class="nav nav-tabs" id="editor-setup" role="tablist">
  <li class="nav-item">
    <a class="nav-link active" id="windows-tab" href="#windows" role="tab" aria-controls="windows" aria-selected="true">Windows</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" id="macos-tab" href="#macos" role="tab" aria-controls="macos" aria-selected="false">macOS</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" id="linux-tab" href="#linux" role="tab" aria-controls="linux" aria-selected="false">Linux</a>
  </li>
</ul>

{% comment %} Tab panes {% endcomment -%}
<div id="sdk-archives" class="tab-content">
{% include_relative _os.md os="Windows" %}
{% include_relative _os.md os="macOS" %}
{% include_relative _os.md os="Linux" %}
</div>

## Master channel

Installation bundles are not available for master.
However, you can get the SDK directly from
[GitHub repo][] by cloning the master channel,
and then triggering a download of the SDK dependencies:

```terminal
$ git clone -b master https://github.com/flutter/flutter.git
$ ./flutter/bin/flutter --version
```

For additional details on how our installation bundles are structured,
see [Installation bundles][].

[Flutter Spring 2020 Update]: {{site.flutter-medium}}/flutter-spring-2020-update-f723d898d7af
[Flutter’s channels]: {{site.repo.flutter}}/wiki/Flutter-build-release-channels
[GitHub repo]: {{site.repo.flutter}}
[Installation bundles]: {{site.repo.flutter}}/wiki/Flutter-Installation-Bundles
