# Supporting Student Oversight of AI-Generated Coursework Deadline Suggestions
README prose word count: XXX

An interactive prototype supporting student review of AI-extracted coursework deadlines and suggested personal target dates.

## Project Status
Currently implemented: A basic webpage with editable coursework name and official deadline fields. A button generates a simulated personal target date three days before the official deadline and displays an explanation. I tested that changing the deadline updates the suggestion correctly.

Not yet implemented: Simulated AI extraction of official deadlines, student editing and approval of suggested dates, rejection of suggestions, and a simulated calendar. No real AI model or calendar integration is used.

## Technology Stack
HTML provides the page structure and input fields. CSS and JavaScript are planned for styling and interactive, rule-based suggestions. No external AI model or API is connected.

## Running or Inspecting the Work
Download or clone the repository and open index.html in a web browser. No installation or dependencies are required.

## Development Record
Stage 1 - Initial screen: Created index.html with coursework name and official deadline fields. I started with a simple interface so students could review coursework information before receiving AI suggestions. I checked that the webpage displayed correctly in my browser.

Stage 2 - Simulated target date suggestion: Added a button that generates a personal target date three days before the official coursework deadline, with a short explanation. I used a fixed rule to simulate an AI suggestion without connecting a real AI model. I tested the feature by changing the official deadline from 18 to 20 December 2026 and checking that the suggested date change from 15 to 17 December 2026.

## AI Assistance
I used ChatGPT to help me learn HTML by providing example code and explaining how it works. I reviewed the explanations to understand the code and checked that the webpage displayed correctly in my browser.

## Additional Files
No additional files or ZIP files are included at this stage.