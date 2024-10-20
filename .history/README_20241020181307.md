# Collaborative Cooking Web Application - Blend & Grow

Blend and Grow, is a web-based collaborative cooking tool designed to foster cross-cultural relationships among international students living in shared accommodations. It allows users to share recipes, assign cooking tasks, and engage in meaningful cultural exchanges through interactive cooking sessions.

## Live Demo

The application is deployed and accessible at: [[Blend & Grow](https://devashrisamani.github.io/SMC/addchefs.html)]

## Features

### 1. Chef Registration and Adding Recipe

- Add multiple housemates who will cook together
- Link recipe URLs for collaborative cooking
- Save recipes for later (simulated feature)

### 2. Ingredient Management

- Automatic generation of ingredient lists from recipes (simulated feature)
- Add/delete ingredients as needed
- Restore original ingredient list with refresh option
- Recipe analysis retry option (simulated feature)

### 3. Task Distribution

- Automatic assignment of cooking tasks to housemates
- Ensures fair distribution with at least one task per person
- Features include:
  - Manual task rearrangement
  - Individual task assignment
  - Random task distribution
  - Reset task assignments
  - Task deletion
  - Adjustable timers for tasks

## Project Structure

Prototype/
│
├── .history/ # History folder
│
├── images/ # Image assets
│ ├── Adding Chefs PNG
│ ├── Logo Brand Colour
│ └── Logo White Colour
│
├── meeting_image/ # Meeting images folder
│
├── addchefs.html # Add chefs functionality page
├── assign.html # Task assignment page
├── index.html # Main entry page
├── url.html # Recipe URL handling page
├── styles.css # Global stylesheet
└── README.md # Project documentation

## Technologies Used

- HTML5
- CSS3
- JavaScript (internal scripting)
- Local Storage for data management

## Setup and Deployment

### Local Development

1. Clone the repository:
   ```bash
   git clone [your-repository-url]
   ```

Open index.html in a web browser to run locally

GitHub Pages Deployment
The website is automatically deployed through GitHub Pages:

Navigate to the repository settings
Under GitHub Pages section, select main branch as source
Save the settings
Access the deployed site at the provided GitHub Pages URL

Usage Guide

Adding Chefs

Open the application
Enter housemate names in the input field
Click "Add" to include them in the cooking session

Recipe Management

Paste recipe URL in the designated field
Use "Save for Later" to bookmark recipes (simulated)

Ingredient Management

Review auto-generated ingredient list
Add or remove ingredients as needed
Use refresh to restore original list
"Retry Analysis" for recipe parsing issues (simulated)

Task Distribution

Review automatically assigned tasks
Rearrange tasks manually if needed
Use random assignment for fair distribution
Adjust timers for each task
Delete unnecessary tasks

Browser Compatibility

Chrome (recommended)
Firefox
Safari
Edge

Known Limitations

Save for Later feature is simulated
Retry Analysis is simulated
All data is stored locally and will be cleared when browser cache is cleared

Contributing
Instructions for how others can contribute to your project, if applicable.
License
[Your chosen license]
Contact
[Your contact information or where to report issues]
Copy
This README.md provides:

1. Project overview
2. Feature list
3. Setup instructions
4. Usage guide
5. Technical details
6. Project structure
7. Browser compatibility
8. Known limitations

Would you like me to expand on any section or add additional information?
