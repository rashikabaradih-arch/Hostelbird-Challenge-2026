
# Hostelbird Product Audit & Engineering Solutions

This project is a submission for the Build, Break, and Ship Hackathon. I have identified 5 critical bugs/gaps in the Hostelbird app and provided technical logic to fix them.

## Identified Bugs

 1. Empty City "Dead-Ends"
- Problem: Clicking certain cities (like Darjeeling) shows "No properties found."
- Fix: The UI should only display city options that have at least 1 active property.

 2. Limited City Selection
- Problem: Users are restricted to a small list of cities with no search bar.
- Fix:Implement a search input with auto-complete to allow users to find any destination.

 3. Unfiltered Social Feed
- Problem: The social feed is global, making it hard to find partners for a specific location.
- Fix:Add a "Search by City" filter to the Social tab so users only see relevant travel buddies.

 4. Solo Mode Logic Conflict
- Problem: Even when "Female Solo Traveller" is ON, the app allows adding multiple adults/children.
- Fix: Logic should auto-lock the guest count to 1 when Solo Mode is active.

 5. Indian Language Gap
- Problem: The app has many foreign languages but lacks major Indian regional languages like Telugu, Tamil, and Bengali.
- Fix: Add localization support for major Indian regional languages to better serve the local market.

Proof of Implementation
- Evidence: See the `bug1.jpg.jpeg` through `bug5.jpg.jpeg` files in this repository.
- Logic Fixes: See `solutions.cpp` for the C++ code demonstrating the validation and filtering logic.
