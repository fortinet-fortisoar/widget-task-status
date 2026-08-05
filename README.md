# Task Status

## Release Information

- **Version**: 1.0.0
- **Certified**: No
- **Publisher**: Fortinet
- **Compatibility**: FortiSOAR 7.6.2 and later
- **Applicable**: View Panel

## Overview

The **Task Status** widget displays a timeline of tasks on a record's detail view, showing the current status of each task at a glance. Each task entry shows a title, a timestamp, a description, and a status indicator — making it easy for analysts to track task progress without leaving the record.

The widget reads task data from a JSON field on the record. That field can be populated by a playbook, via the FortiSOAR REST API, or by editing the field directly on the record.

> [!NOTE]
> The **Task Status** widget is currently available only on the Alerts detail view.

### Key Features

- Display a list of tasks with their current status on a record's detail view
- Visualize task status using distinct icons: completed, in progress, queued, awaiting user input, and failed
- Show task title, timestamp, and description for each task entry
- Highlight the in-progress task for quick identification
- Update the task list in real time as the underlying field value changes

## Next Steps

| [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) |
| -------------------------------------------- | ---------------------------------------------- | ------------------------ |