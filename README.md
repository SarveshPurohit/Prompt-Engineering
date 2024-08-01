# Prompt-Engineering
I used following prompt instructions to prompt ChatGPT to parse a resume document into json format.

I'm giving you a resume document as input. Your task is to parse the content in JSON format.
The JSON object should represent the key sections and details found in a resume. The resume is composed of several sections, each containing specific information about the candidate. Below are the instructions for structuring the resume data into JSON:

Sections of the Resume:
Personal Information: This section includes the candidate's basic details such as name, contact information, and address.

Fields:

name: The full name of the candidate.
contact: An object containing:
phone: The candidate's phone number.
email: The candidate's email address.
address: An object containing:
street: The street address (if provided).
city: The city (if provided).
state: The state or region (if provided).
zip: The postal code (if provided).
Education: A list of educational qualifications, including the institution name, degree, field of study, and graduation date.

Fields:

education: An array of objects, each representing an educational qualification with:
institution: The name of the educational institution.
degree: The degree obtained.
fieldOfStudy: The field of study.
graduationDate: The graduation date.
Relevant Coursework: A list of courses relevant to the candidate's field of study.

Fields:

coursework: An array of strings, each representing a course.
Projects: A list of projects undertaken by the candidate, including project name, technologies used, and a brief description.

Fields:

projects: An array of objects, each representing a project with:
name: The name of the project.
technologies: An array of strings representing the technologies used.
description: A string describing the project.
Publications: A list of publications by the candidate, including publication name and date.

Fields:

publications: An array of objects, each representing a publication with:
title: The title of the publication.
date: The date of publication.
conference: The conference or journal where it was presented or published.
Technical Skills: A list of technical skills relevant to the candidate's professional expertise.

Fields:

technicalSkills: An object containing:
languages: An array of strings, each representing a programming language.
developerTools: An array of strings, each representing a development tool.
technologies: An array of strings, each representing a technology or framework.
Certifications (optional): A list of certifications obtained by the candidate.

Fields:

certifications: An array of objects, each representing a certification with:
name: The name of the certification.
authority: The issuing authority.
date: The date of certification.
Example JSON Output:
Here is an example of how the JSON object should look based on the provided resume data:
xyz.json file was given to ChatGPT as an example json object

Make sure each section and field in the JSON output is populated based on the corresponding details from the resume document. Use this structure and instructions as a template for parsing resumes into a JSON format. Adapt the fields and sections as necessary to fit the specific details provided in each resume.
Once you have understood the instructions I'll be ready to give a sample resume for you to parse.

Response:
response.json file, which is present in this repository was received as a response for Rahul_Sharma_Resume.docx file.
