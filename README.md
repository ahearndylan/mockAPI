# Mock API for Digital Bar Card Project

## Overview

This is a mock API created for the **Digital Bar Card** proof-of-concept project. It simulates interactions with the Massachusetts Board of Bar Overseers (BBO) database and allows developers to test lawyer credential verification without relying on a real external API.

This API was built to support the development and demo of a digital credentialing system for Massachusetts lawyers.

## Features

- Simulates lawyer credential verification
- Returns mock lawyer data, including:
  - Name
  - BBO number
  - Status (active/inactive)
  - Discipline history
  - Bar dues payment status

## Example Users

| Name            | Status  | Discipline | Dues Paid |
|-----------------|---------|------------|-----------|
| Robert Ahearn   | Active  | None       | Yes       |
| Ashley Ahearn   | Active  | None       | Yes       |
| John Glynn      | Active  | Yes        | Yes       |
| Timothy Smith   | Active  | None       | No        |

## Tech Stack

- Python
- Django REST Framework

## Project Use

This API is intended **for demonstration purposes only** and does not represent a live or official government service.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this code, provided that proper credit is given.

© 2024 Dylan Ahearn
