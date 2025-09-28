# Claude Instructions for Zendesk Email Theme

## Project Overview
This project contains Socket's custom email template for Zendesk notifications. The template includes Socket branding, responsive design, and all required Zendesk placeholders.

## File Structure
- `claude.md` - This file containing project instructions
- `email-template.html` - The Zendesk email template with Socket branding
- `README.md` - Project documentation (if needed)

## Development Workflow
- When you're done with a task, commit changes to GitHub every time
- Use descriptive commit messages
- Keep the template responsive and accessible
- Test changes across different email clients when possible

## Template Requirements
- **Logo**: Socket logo (https://socket.dev/images/logo-280x80.png)
- **Header background**: Purple `#553C9A`
- **Font**: Euclid Circular B with system font fallbacks
- **Body background**: Light gray `#f7f7f9`
- **Content block**: White background, rounded corners, padding, subtle shadow
- **Footer**: Centered, smaller font, muted color `#49545c`
- **Responsive**: Mobile-friendly design
- **Zendesk placeholders**: Must preserve `{{content}}`, `{{footer}}`, `{{footer_link}}`, `{{quoted_content}}`, `{{lang}}`, `{{attributes}}`, `{{styles}}`

## Usage
The `email-template.html` file should be copied into Zendesk's email template settings under Admin > Channels > Email > Templates.