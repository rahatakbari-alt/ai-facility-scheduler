# AI Facility Scheduler

## Overview

The AI Facility Scheduler is a web-based application designed to help recreation facilities optimize space usage and reduce manual scheduling effort.

## Live Application

Access the deployed application here:
https://rahatakbari-alt.github.io/ai-facility-scheduler/

## Problem Statement
Recreation facilities face inefficiencies in scheduling due to:
- Manual booking systems
- Double bookings
- Lack of real-time visibility

## Business Impact
- Lost revenue from unused slots
- Staff inefficiency
- Poor customer experience

## Solution

This application uses AI-assisted logic to analyze scheduling data and identify available time slots across multiple rooms.

## Features

* Upload schedule via CSV (CRM export)
* Multi-room support (Gym, Pool, Meeting Rooms)
* AI-recommended best time slot
* Automated availability detection
* Clean and simple user interface

## How It Works

1. The user uploads a CSV file containing scheduling data (Room, Start Time, End Time)
2. The system parses and organizes bookings by room
3. It identifies gaps between scheduled bookings within operating hours (7 AM – 11 PM)
4. It calculates the duration of each available time slot
5. The system recommends the longest available time slot as the optimal booking option

Note: The current system uses rule-based logic for recommendations, with future potential for more advanced AI-driven optimization.

## Tech Stack

* HTML, CSS, JavaScript
* Replit (AI-assisted development environment)
* ChatGPT (used for ideation, coding, and debugging)

## How to Use

1. Open index.html in a web browser
2. Upload a CSV file with columns:
   - Room
   - Start Time
   - End Time
3. Click "Find Open Slots"
4. View AI-recommended time slots

## AI-Assisted Development

AI tools were used throughout the entire development process:

- ChatGPT: Used for ideation, feature design, debugging, and refining application logic
- Replit AI: Used for generating and iterating on code directly within the development environment

The development process involved iterative prompt engineering, where outputs were continuously refined to improve functionality and accuracy.

AI acted as a co-developer, accelerating development while requiring human validation and testing to ensure correctness and usability.

### Example Prompt Used

"Add a file upload feature that accepts CSV files with columns Room, Start Time, and End Time, and use this data to calculate available time slots."

### Key Insight

AI significantly accelerated development but required human validation...

## Business Value

This application helps recreation facilities:
- Reduce manual scheduling time
- Improve space utilization
- Minimize booking conflicts
- Enable faster decision-making

## Current Limitations

- The system uses simplified (rule-based) logic rather than advanced AI models
- Performance depends on the quality of uploaded data
- No real-time integration with external booking systems

These limitations represent opportunities for future development.

## Future Improvements

- Integration with real CRM systems
- Advanced AI-based scheduling optimization
- Real-time booking updates
- Multi-user support

## System Flow

CSV Upload → Data Processing → Availability Detection → Recommended Time Slot Output

## Team Members

* Rahat Akbari, Hajra Anwar, Mohamad Hemadi, Olutito Mebude, and Nolan Sun 

## License

MIT License
