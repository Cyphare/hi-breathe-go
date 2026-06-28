# Updating Website Content

All of the website's dynamic content is managed through simple YAML files located in the `data/` directory. You do not need to write any code to add or update content.

## How to add or edit content

1. Navigate to the `data` folder in the repository.
2. Open the file corresponding to the section you want to update:
   - `about.yaml` - Modify the about text or mission statement.
   - `publications.yaml` - Add new papers or publications.
   - `research.yaml` - Update research topics, projects, or news.
   - `students.yaml` - Add or remove student profiles.
   - `team.yaml` - Add or update team members.
3. Copy an existing entry (block of text) from the file to use as a template.
4. Paste the copied block where you want the new entry to appear, and replace the details with your new content.
5. Save the file and commit your changes. The website will automatically update with the new information.

## Important rules for editing YAML
- **Indentation matters**: Always use spaces (not tabs) to align your entries exactly like the existing ones.
- **Special characters**: If your text contains colons (`:`), single quotes (`'`), or double quotes (`"`), wrap the entire text field in quotes (e.g., `title: "New Paper: A Study"`).
- **Images**: When referencing an image, place the image file in the `static/` directory (e.g., `static/images/`) and reference it in the YAML file starting with `/` (e.g., `/images/my-photo.jpg`).
