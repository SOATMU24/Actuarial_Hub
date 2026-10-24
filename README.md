# Actuarial Science Hub

### Tom Mbiya University | Academic Resource Centre

Actuarial Science Hub is a central academic resource platform designed to help students access learning materials, examination papers, academic notices, career opportunities and research resources.

## Objectives

- Make academic resources easy to find and download.
- Organise materials by unit code, academic year and semester.
- Support preparation for examinations and assessments.
- Share approved internship and career opportunities.
- Support research, projects and data-analysis learning.
- Help the course executive coordinate academic information.

## Resource Categories

1. Lecture Notes
2. Past Examination Papers
3. Exam Timetables and Notices
4. Internships and Career Opportunities
5. Research Projects and Datasets
6. Course Executive Contact Information
7. Student Academic Support

## Search Features

The website supports searching by:

- Resource title and keywords
- Unit code, such as MAC 201
- Resource category
- Examination year
- Academic year of study
- Semester
- File description

Examination-year options are generated from the examination papers listed in the resource catalogue.

## Repository Structure

```text
actuarial-science-hub/
├── index.html
├── resources.json
├── assets/
├── notes/
├── past-papers/
├── notices/
├── careers/
├── research/
├── contacts/
└── support/
```

## Adding Resources

Only authorised administrators may publish, replace or remove resources.

1. Verify the document and its permission for public distribution.
2. Upload it to the appropriate repository folder.
3. Add its metadata to `resources.json`.
4. Include its title, unit code, category, year, semester, description and file path where applicable.
5. Review the changes and verify that the search result and download link work.
6. Publish the approved changes.

For past papers, use the `examYear` field to identify the examination year.

Example:

```json
{
  "title": "MAC 201 Past Paper 2025",
  "unitCode": "MAC 201",
  "category": "Past Papers",
  "examYear": 2025,
  "academicYear": "Year 2",
  "semester": "Semester 1",
  "description": "MAC 201 examination paper for revision.",
  "fileType": "PDF",
  "filePath": "past-papers/MAC-201/MAC-201-2025.pdf",
  "keywords": ["mathematics", "revision"]
}
```

Ensure the file exists at the specified path before publishing its catalogue entry.

## Administration and Access

- The repository is public so approved materials can be accessed through a public link.
- Only authorised managers should have write access.
- Repository administration should remain limited to trusted owners.
- Use pull-request reviews to help prevent accidental or unauthorised changes.
- Student support submissions and confidential academic records must be stored separately from public files.

## Publishing

GitHub Pages is used to host the public website.

Recommended configuration:

- Publishing source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`
- Entry page: `index.html`

The searchable catalogue is loaded from `resources.json`.

## Responsible Use

- Publish only materials approved for distribution.
- Respect copyright and university policies.
- Verify the accuracy of notices and opportunities.
- Remove expired announcements when appropriate.
- Do not publish student grades, registration lists, passwords or private support requests.

## Maintenance

Administrators should review resource links, update examination papers, remove outdated opportunities and maintain backup copies regularly.

---

Actuarial Science Hub  
Tom Mbiya University  
Academic resources for student learning and development.
