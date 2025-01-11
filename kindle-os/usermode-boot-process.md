---
layout: default
title: Usermode Boot Process
parent: Kindle OS
nav_order: 1
has_children: true
---
# Usermode Boot Process
The Kindle uses upstart for its usermode boot process.

Below is a diagram generated from all the Kindle's (PW6) upstart services.
[Fullscreen Version](./upstart-diagram.html){: .btn .btn-purple }

<style>
    .language-mermaid svg {
        height: 70vh;
    }
</style>

<iframe style="width: 100%; height: 100vh;" src="./upstart-diagram.html"></iframe>