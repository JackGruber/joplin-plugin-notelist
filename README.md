<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD028 -->
<!-- markdownlint-disable MD007 -->
<!-- markdownlint-disable MD045 -->

# Joplin note list preview <img src=img/icon_32.png>

A plugin to add a previw to the note list.

<img src=img/main.png>

<!-- prettier-ignore-start -->

<!-- TOC depthfrom:2 orderedlist:false -->

- [Installation](#installation)
    - [Automatic](#automatic)
    - [Manual](#manual)
- [Usage](#usage)
- [Plugin options](#plugin-options)
- [Layouts](#layouts)
    - [Layout 1](#layout-1)
        - [Layout 1 - Thumbnail right](#layout-1---thumbnail-right)
        - [Layout 1 - Thumbnail left](#layout-1---thumbnail-left)
        - [Layout 1 - No thumbnail](#layout-1---no-thumbnail)
    - [Layout 2](#layout-2)
        - [Layout 2 - Thumbnail right](#layout-2---thumbnail-right)
        - [Layout 2 - Thumbnail left](#layout-2---thumbnail-left)
        - [Layout 2 - No thumbnail](#layout-2---no-thumbnail)
- [Examples with settings](#examples-with-settings)
    - [Date and Tags](#date-and-tags)
    - [Thumbnail right](#thumbnail-right)
- [Changelog](#changelog)

<!-- /TOC -->

<!-- prettier-ignore-end -->

## Installation

### Automatic

- Go to `Tools > Options > Plugins`
- Search for `Note list (Preview)`
- Click Install plugin
- Restart Joplin to enable the plugin

### Manual

- Download the latest released JPL package (`io.github.jackgruber.notelistpreview.jpl`) from [here](https://github.com/JackGruber/joplin-plugin-notelistpreview/releases/latest)
- Close Joplin
- Copy the downloaded JPL package in your profile `plugins` folder
- Start Joplin

## Usage

The new note list view can be activated under `View > Note list style > Preview`.
<img src=img/enable.png>

## Plugin options

Settings for the plugin, accessible at `Tools > Options > Note overview`.
Joplin must be restarted after changing settings!

## Layouts

### Layout 1

#### Layout 1 - Thumbnail right

<img src=img/layout1_img_r.svg>

#### Layout 1 - Thumbnail left

<img src=img/layout1_img_l.svg>

#### Layout 1 - No thumbnail

<img src=img/layout1.svg>

### Layout 2

#### Layout 2 - Thumbnail right

<img src=img/layout2_img_r.svg>

#### Layout 2 - Thumbnail left

<img src=img/layout2_img_l.svg>

#### Layout 2 - No thumbnail

<img src=img/layout2.svg>

## Examples with settings

### Date and Tags

<img src=img/example_tag.png>

| Setting | Value |
| ------- | ----- |
| Note excerpt | 115 |
| Last line | {{tags}} |

### Thumbnail right

<img src=img/example_thumbnail_right.png>

| Setting | Value |
| ------- | ----- |
| Thumbnail | Right |
| Note excerpt | 100 |

## Changelog

See [Changelog](CHANGELOG.md)
