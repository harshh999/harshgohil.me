# Resume Setup Instructions

## To add your resume to the portfolio:

1. **Create your resume PDF**
   - Export your resume as a PDF file
   - Name it exactly: `resume.pdf`
   - Place it in this `public` folder

2. **Update the download link**
   - The hero section currently links to the contact section
   - Once you add `resume.pdf`, you can update the hero component to link directly to the PDF:
   
   ```tsx
   // In components/hero.tsx, change:
   href="#contact"
   // to:
   href="/resume.pdf"
   target="_blank"
   rel="noopener noreferrer"
   ```

3. **Alternative: Link to external resume**
   - You can also link to Google Drive, Dropbox, or any other hosting service
   - Just replace the href with your external link

## Current Status
- Resume download button currently redirects to contact section
- Add your `resume.pdf` file here to enable direct download
- The button text will make sense once the PDF is added

## File Structure
```
public/
├── resume.pdf          <- Add your PDF here
└── README-RESUME.md    <- This instruction file
```