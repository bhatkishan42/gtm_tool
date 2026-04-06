# gtm_tool

Automated GTM SOP Builder for Teams.

## Overview

A template-driven tool to streamline the creation and management of Google Tag Manager (GTM) configurations. It helps teams standardize tagging workflows and generate reusable SOPs efficiently.

## Features

- Template-driven creation for tags, triggers, and variables
- Save current setup as reusable custom templates
- Store templates in browser using localStorage
- Build multi-item SOP bundles
- Export combined JSON for all items
- One-click export with filename:
  `extract_all_tags_triggers_variables.json`

## What It Supports

- Tags
- Triggers
- Variables
- SOP bundle creation
- Template management

## Use Case

Ideal for analytics teams and developers who want to:
- Standardize GTM implementation
- Reduce manual setup time
- Maintain consistency across projects

## Export Output

All configured items can be exported as a single JSON file containing:
- Tags
- Triggers
- Variables

Default export file:
`extract_all_tags_triggers_variables.json`
