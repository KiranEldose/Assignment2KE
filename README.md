# Supporting Student Oversight of AI-Generated Coursework Deadline Suggestions
README prose word count: XXX

An interactive prototype supporting student review of AI-extracted coursework deadlines and suggested personal target dates.

## Project Status
Implemented: Editable coursework details, simulated personal target suggestions (three days before the official deadline), date editing, approval and rejection, and a simulated monthly calendar. The calendar distinguishes personal targets from officia deadlines and supports multiple assignments.

Not yet implemented: Simulated AI extraction of official deadlines. No real AI or calendar integration is used.

## Technology Stack
HTML provides the page structure and input fields. CSS and JavaScript are planned for styling and interactive, rule-based suggestions. No external AI model or API is connected.

## Running or Inspecting the Work
Download or clone the repository and open index.html in a web browser. No installation or dependencies are required.

## Development Record
Stage 1 - Initial interface: Created coursework name and deadline fields and checked that the webpage displayed correctly.
Stage 2 - Simulated suggestions: Added a rule-based target date suggestion with an explanation. Tested differnt deadlines to confirm the suggested date changed correctly.
Stage 3 - Student control: Added editing, approval and rejection. Included validation to prevent personal targets after the official deadline and prevented duplicate entries wheen reapproving coursework.
Stage 4 - Simulated calendar: Added colour-coded coursework labels and month navigation. Tested navigation and overlapping assignment deadlines to check that multiple events remained visible.

## AI Assistance
I used ChatGPT to help me learn HTML by providing example code and explaining how it works. I reviewed the explanations to understand the code and checked that the webpage displayed correctly in my browser.

## Additional Files
No additional files or ZIP files are included at this stage.