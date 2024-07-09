# Widget Documentation: My Agile Stories Widget

## Overview

The My Agile Stories Widget is a custom widget developed for ServiceNow Employee Center. It retrieves and displays agile stories assigned to the current logged-in user from both `rm_story` and `sn_safe_story` tables.

## Features

- Displays agile stories assigned to the logged-in user.
- Retrieves stories from `rm_story` and `sn_safe_story` tables.
- Shows story details such as short description, state, and end date.
- Allows users to click on a story to view details in a new tab.

## Usage

### Viewing Agile Stories

- Once added to the Employee Center page, the widget will automatically fetch and display agile stories assigned to the current user.
- Stories from both `rm_story` and `sn_safe_story` tables are included based on the logged-in user's assignments.

### Interaction

- Click on a story listed in the widget to view its details. The story will open in a new tab for detailed review or further action.
