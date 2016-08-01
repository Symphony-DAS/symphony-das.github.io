---
layout: default
title: Home
---

<img src="public/images/logo.png" srcset="public/images/logo.png 1x, public/images/logo@2x.png 2x" alt="Symphony Logo">

<h1>Simple, Powerful, Extensible<br>
Protocol-Driven Acquisition in MATLAB&reg;</h1>

<a href="{{ site.github.repo }}/releases/download/{{ site.version }}/Symphony.mlappinstall" class="btn">Download</a>
<a href="{{ site.github.repo }}" class="btn">GitHub</a>

<hr>

## What is Symphony?
Symphony is a MATLAB based data acquisition system for electrophysiologists. It provides a framework for writing acquisition routines and a user interface to conduct experiments.

![hero](public/images/hero.png)

<a href="{{ site.gitbook.book }}/content/" class="btn">Documentation</a>

<hr>

## Protocol-Driven Acquisition
Symphony is centered around protocol-driven acquisition. Protocols are high-level acquisition routines you write in MATLAB using the Symphony framework. You can write protocols with sophisticated online analysis and gap-free recording.

![protocol](public/images/protocol.png)

<p><label class="btn collapse-toggle">View an Example Protocol</label></p>
<div class="collapse">
  <script src="https://gist.github.com/cafarm/0ad2661c46829cbc727fbdbf345d2a7c.js"></script>
</div>

<hr>

## Built-in Data Manager
Symphony includes a built-in data manager to browse, view, and annotate data during experiments. You can use the data manager to maintain visibility across the entire experimental timeline.

![data manager](public/images/data-manager.png)

<hr>

## Flexible Data Model
Symphony uses a flexible data model that supports a wide variety of organizational approaches. You can write simple descriptions to define the experimental structure and metadata that best suits your needs.

![metadata](public/images/metadata.png)

<p><label class="btn collapse-toggle">View an Example Description</label></p>
<div class="collapse">
  <script src="https://gist.github.com/cafarm/b334cd0cf11ded942a12a1f8de8796f7.js"></script>
</div>

<hr>

## Modular and Extensible
Symphony was built from the ground up to be modular and extensible. At the app-level you can write modules to add custom features to the user interface. At the core-level you can write implementations to add support for additional hardware and file formats.

![modular](public/images/modular.png)

<hr>

## Device-Agnostic Programming Interface
Symphony abstracts away device-specific details that allow your acquisition routines to be hardware independent. You can share your protocols across experimental rigs with limited or no modification.

![devices](public/images/devices.png)

<hr>

## Free and Open Source
Symphony is released under the [MIT License](https://opensource.org/licenses/MIT), which is an [open source license](https://opensource.org/docs/osd). You can share and change the source code to your heart's content!

<img src="public/images/osi.png" srcset="public/images/osi.png 1x, public/images/osi@2x.png 2x" alt="OSI Logo">

<hr>

&copy; {{ site.time | date: '%Y' }} Symphony-DAS. MATLAB is a registered trademark of The MathWorks, Inc. The OSI logo trademark is the trademark of Open Source Initiative.
