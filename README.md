# Project Scheduler - P6 Style

A web-based project scheduling and Gantt chart application styled to resemble Oracle Primavera P6. This interactive tool allows you to manage project activities, visualize timelines, calculate critical paths, and track project progress.

access the app at: https://vinitawagh-maker.github.io/Vinita-Test/


## Features

### 📊 Gantt Chart Visualization
- Interactive Gantt chart with timeline view
- Visual representation of task durations and dependencies
- Color-coded tasks (normal, critical, complete)
- Milestone markers (diamond-shaped indicators)
- Dependency lines showing relationships between activities
- Zoom in/out functionality for detailed or overview views

### 📋 Activity Management
- **Add Activities**: Create new project activities with customizable properties
- **Edit Activities**: Double-click any task to edit its details
- **Delete Activities**: Remove tasks from the project schedule
- **Activity Properties**:
  - Activity ID (auto-generated)
  - Activity Name
  - Duration (in days)
  - Start and Finish dates
  - Percentage complete
  - Predecessors (dependencies)
  - Activity Type (Task or Milestone)

### 🔴 Critical Path Analysis
- Automatic calculation of the critical path through the project
- Visual highlighting of critical activities in red
- Forward and backward pass calculations
- Identifies activities with zero float (critical tasks)

### 📈 Project Tracking
- Progress bars showing completion percentage for each activity
- Color indicators:
  - **Blue**: Normal activities
  - **Red**: Critical path activities
  - **Green**: Completed activities (100%)
- Project data date tracking
- Real-time updates when activities are modified

### 🎨 User Interface
- Dark theme inspired by Primavera P6
- Split-screen layout:
  - Left panel: Activity table with all task details
  - Right panel: Interactive Gantt chart
- Responsive design with smooth scrolling
- Hover effects and visual feedback
- Custom scrollbars for better aesthetics

## How to Use

1. **Open the Application**: Simply open `index.html` in a modern web browser (Chrome, Firefox, Edge, Safari)

2. **View Sample Data**: The application loads with sample construction project data to demonstrate functionality

3. **Add a New Activity**:
   - Click the "Add Activity" button in the toolbar
   - A new activity will be created and the edit modal will open
   - Fill in the activity details and click "Save"

4. **Edit an Activity**:
   - Double-click any activity in the table or Gantt chart
   - Modify the activity properties in the modal
   - Click "Save" to apply changes

5. **Set Dependencies**:
   - In the edit modal, enter predecessor activity IDs (e.g., "A1010, A1020")
   - Dependencies will be shown as connecting lines in the Gantt chart

6. **Calculate Critical Path**:
   - Click the "Critical Path" button in the toolbar
   - Critical activities will be highlighted in red

7. **Zoom Controls**:
   - Use the zoom in/out buttons to adjust the timeline scale
   - Useful for viewing detailed schedules or getting an overview

8. **Delete Activities**:
   - Select an activity by clicking on it
   - Click the "Delete" button in the toolbar

## Technical Details

- **Technology Stack**:
  - Pure HTML, CSS, and JavaScript (no build process required)
  - Tailwind CSS (via CDN) for styling
  - Font Awesome icons for UI elements
  - SVG for dependency line rendering

- **Browser Compatibility**: Works in all modern browsers that support ES6 JavaScript

- **Data Storage**: Currently stores data in memory (refreshing the page resets to sample data)

## Sample Project Structure

The application comes pre-loaded with a sample construction project including:
- Project Kickoff (Milestone)
- Site Preparation
- Foundation Work
- Structural Steel
- Electrical & Plumbing Rough-in
- HVAC Installation
- Interior Finishing
- Final Inspection
- Project Complete (Milestone)

## Future Enhancements

Potential improvements could include:
- Data persistence (localStorage or backend integration)
- Export to PDF/Excel
- Resource allocation
- Baseline comparison
- Calendar view
- Filtering and sorting options
- Undo/Redo functionality

## License

This project is available for use and modification.
