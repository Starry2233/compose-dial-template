# Compose Dial Template

XTC compose dial project template — config-driven watch face composed of multiple .pl plugin elements.

## Structure

```
├── config.json       # NetComposeDial JSON definition
├── deploy.json       # Deployment info
└── target/           # Deployment target (created by XTC Dial Factory)
```

## Usage

1. Click **"Use this template"** to create a new repo
2. Edit `config.json` to define your plugin elements (time, date, battery, etc.)
3. Deploy to device via XTC Dial Factory or manually

## What is a Compose Dial?

A compose dial combines multiple independent .pl plugin components into a single watch face using a JSON configuration file. Each element specifies its position, size, plugin source, and optional parameters.

## Element Types

| type | Description |
|------|-------------|
| 1    | Normal component (time, date, battery, custom) |
| 7    | Background component (fullscreen, GIF or image) |
| 11   | Text component (self_text, custom text) |
