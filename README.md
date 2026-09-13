# Inky Message Plugin for InkyPi

Inky Message is a simple and flexible plugin for creating and displaying custom messages on InkyPi e-paper displays

It includes a lightweight rich text editor with multiple font sizes, text styles, alignment options, optional timestamps, and customizable message bubbles

## Install

Install the plugin using the InkyPi CLI, providing the plugin ID and GitHub repository URL:

    inkypi plugin install inky_message https://github.com/saulob/InkyPi-Inky-Message

This plugin is an extension for the [InkyPi](https://github.com/fatihak/InkyPi) e-paper display frame and includes the following features:

## Features

- Create and display custom messages
- Built-in lightweight rich text editor
- Multiple font sizes inside the same message
- Bold text formatting
- Italic text formatting
- Underline text formatting
- Left, center, right and justified text alignment
- Optional timestamp
- Optional message bubble style
- Customizable bubble color
- Dynamic bubble height based on message content
- Automatic text wrapping
- Supports different screen sizes and orientations
- Optimized for e-paper displays
- No external APIs required

## Text Editor

The message editor provides simple WYSIWYG-style formatting directly in the InkyPi settings screen

Available formatting options:

- Font Size
  - Small
  - Medium
  - Large
  - Extra Large
- Bold
- Italic
- Underline
- Align Left
- Align Center
- Align Right
- Justify

Formatting can be applied to individual words, selections or paragraphs, allowing different styles inside the same message

## Settings

### Message

Rich text editor used to create and format the message displayed on the screen

### Show Timestamp

Enables or disables the message timestamp

Default:

    Enabled

When enabled, the timestamp is displayed centered above the message

Examples:

    Today 5:30 PM

or

    Sep 13, 5:30 PM

### Bubble Style

Enables or disables the message bubble layout

Default:

    Enabled

When enabled, the message is displayed inside a rounded message bubble inspired by common messaging applications

When disabled, the message is rendered using the plain layout

### Bubble Color

Sets the background color of the message bubble

The default color is a light gray inspired by the standard iPhone SMS message bubble

This setting only applies when Bubble Style is enabled

### Style

Standard InkyPi style settings remain available for display customization

## Message Bubble

The optional Message Bubble style gives messages a more recognizable messaging-app appearance

Features:

- Rounded corners
- Small message tail on the lower-left side
- Dynamic height based on the actual message content
- Compact internal padding
- Customizable background color
- Timestamp displayed above the bubble
- Automatic text wrapping
- Full rich text formatting inside the bubble

On horizontal displays, the bubble uses almost the full available width

On vertical displays, the bubble width adapts to the available space while maintaining balanced margins

## Plain Style

When Bubble Style is disabled, the message is displayed directly on the background without a bubble

All text formatting features remain available

## UI / Result

- Clean and minimal message layout
- Rich text formatting rendered directly on the e-paper display
- Optional iPhone-inspired message bubble
- Optional centered timestamp
- Automatic line wrapping
- Mixed font sizes and styles
- Per-paragraph text alignment
- Customizable bubble color
- Layout automatically adapts to message length
- Designed for readability on e-paper displays

## Notes

- No external APIs used
- No network connection required
- Fully self-contained
- Message formatting is stored with the plugin configuration
- Designed to work with horizontal and vertical displays
- Emoji rendering depends on the fonts available on the system and is not currently an official feature

## Screenshots
