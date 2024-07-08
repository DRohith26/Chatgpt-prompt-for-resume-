#ChatGPT Prompt which takes your Resume as input and parse the content in JSON format

Here is my resume in PDF format and have it parsed into a structured JSON format. The resume contains sections such as SUMMARY, EDUCATION, SKILLS, PROJECTS, and CERTIFICATIONS. Please extract the content from each section and organize it accordingly in the JSON output. Here are the steps I'd like you to follow:

Extract the text from the PDF file.

Identify and parse the content under each of the following sections:

Name and contact information (assumed to be the first two lines of the document).
SUMMARY: This section should contain a brief summary or objective.
EDUCATION: This section should list the educational background.
SKILLS: This section should list the skills, ideally parsed as individual items.
PROJECTS: This section should list project descriptions.
CERTIFICATIONS: This section should list any certifications.
Format the extracted information into a JSON structure with the following keys:

name: Full name of the individual.
contact: Contact details (e.g., phone number, email address).
summary: A brief summary or objective statement.
education: A list of educational background entries.
skills: A list of skills.
projects: A list of projects.
certifications: A list of certifications.
