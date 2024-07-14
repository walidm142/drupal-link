# Events Management Module

## Introduction
The Events Management module allows users to manage and display events on a Drupal site.

## Prerequisites
- Drupal 10
- PHP 8.2
- MySQL 8.0

## Installation
1. Clone the repository into your `modules/custom` directory:
    ```bash
    git clone https://github.com/walidm142/drupal-link.git .
    ```

2. Enable the module:
    ```bash
    drush en events_management
    ```

3. Import the views configuration:
    ```bash
    drush config-import
    ```

4. Navigate to the module configuration page to set up:
    ```bash
    /admin/config/events_management
    ```

## Features
- CRUD operations for events.
- Configuration to show/hide past events and set the number of events per page.
- Frontend display of events with a listing page and details page.
- Latest events block to display the latest 5 events.

## Code Documentation
Code documentation is provided within the module files.

## Task Rating
- Attention to details: 5
- Thinking, problem-solving, and decision-making: 5
- Knowledge of Drupal and its features: 5
- Quality of code structure: 5
