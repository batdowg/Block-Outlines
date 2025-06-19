# Workshop Outline Builder

This simple HTML/JavaScript application helps plan multi-day training workshops.  Modules such as lessons or activities can be dragged from the list on the left onto a time grid representing the schedule for each day.  Each module has a duration and may be color coded.

## Features
- Generate a grid for 1–10 days with custom start and end times.
- Drag modules onto the grid to schedule them.
- Move scheduled modules to a new time or back to the module list by dragging.
- Create custom modules with a specific duration and title.
- Module groups (SA, PA, etc.) allow filtering of the module list.
- Edit or delete custom modules from the module list.
- Undo or redo schedule changes.
- Schedules persist in your browser via local storage and can be exported or imported as JSON.
- Export the final schedule as CSV for sharing.
- Optional dark mode for low-light environments.

## Usage
Open `BlockOutlines.html` in a modern browser and click **Generate Grid** to create the schedule layout. Drag items from the module list into the grid. Grab any cell of a scheduled module to move it elsewhere or drag it back to the list to unschedule. Use **Undo**/**Redo** to revert actions. **Export JSON** saves the schedule, while **Import JSON** restores one. **Export CSV** downloads a simple CSV version.
