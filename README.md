# ATS-Friendly Resume Templates

## Project Overview

This project provides downloadable HTML resume templates optimized for Applicant Tracking Systems (ATS). Our templates help job seekers create professional resumes that successfully pass through ATS software while maintaining visual appeal.

## Problem Statement

**What problem are we solving?**

Many job seekers create visually impressive resumes that get rejected by ATS software before reaching human recruiters. Companies use ATS to automatically scan and filter resumes, but these systems struggle with:
- Complex layouts and multi-column designs
- Graphics, images, and icons
- Tables and text boxes
- Non-standard fonts and formatting

**Our solution:** Provide clean, professional HTML resume templates that are specifically designed to be ATS-compatible while still looking polished and professional.

## Solution Approach

### Core Features

1. **ATS-Optimized Structure**
   - Single-column layout for linear parsing
   - Standard section headings (EXPERIENCE, EDUCATION, SKILLS, etc.)
   - Semantic HTML using proper heading tags
   - No tables, images, or complex CSS positioning

2. **Professional Appearance**
   - Clean, modern design
   - Print-friendly formatting
   - Standard, readable fonts
   - Balanced white space

3. **Easy Customization**
   - Self-contained HTML files with inline CSS
   - Clear placeholder text in [BRACKETS]
   - Instructional comments throughout
   - No external dependencies

4. **Multiple Template Styles**
   - Classic Professional
   - Modern Minimal
   - Executive Format
   - Entry-Level Friendly

### Technical Implementation

**File Format:** HTML with embedded CSS

**Key Design Principles:**
- Use semantic HTML5 tags (`<header>`, `<section>`, `<article>`)
- Keep CSS simple and inline
- Avoid floats, flexbox columns, and grid layouts
- Use standard web-safe fonts
- Include `@media print` styles for PDF conversion

## Project Structure

```
ats-resume-templates/
├── README.md
├── index.html (landing page with template previews)
├── templates/
│   ├── classic-professional.html
│   ├── modern-minimal.html
│   ├── executive-format.html
│   └── entry-level.html
└── docs/
    └── customization-guide.md
```

## How to Use

### For Users

1. Browse available templates on the landing page
2. Download the HTML file that matches your style preference
3. Open the file in any text editor (Notepad, VS Code, etc.)
4. Replace placeholder text with your information
5. Open in a browser to preview
6. Print to PDF or submit the HTML file

### For Developers

1. Clone or download the repository
2. Open template files in your code editor
3. Follow the comment instructions for customization
4. Test ATS compatibility using online ATS scanners
5. Preview in browser and test print formatting

## ATS Best Practices Included

Our templates follow these critical ATS guidelines:

- **Standard Section Headers:** Use conventional names like "Work Experience" not "Where I've Been"
- **Simple Formatting:** No columns, tables, or text boxes
- **Standard Fonts:** Arial, Calibri, Georgia, Times New Roman
- **Chronological Order:** Most recent experience first
- **Keywords:** Space for industry-relevant keywords
- **Contact Information:** Clear and at the top
- **File Format:** HTML can be converted to PDF easily
- **No Headers/Footers:** All content in main body

## Getting Started

### Creating Your First Template

1. Start with the problem: What information does ATS need to parse?
2. Structure the solution: Single-column, semantic HTML
3. Add minimal styling: Professional but simple CSS
4. Test thoroughly: Check parsing and print layout
5. Document clearly: Add comments for user guidance

## Future Enhancements

- Interactive web form to fill templates online
- Instant PDF download functionality
- ATS score checker integration
- More industry-specific templates
- Mobile-responsive preview page

## Contributing

When adding new templates, ensure they:
1. Pass ATS parsing tests
2. Print cleanly to PDF
3. Include clear placeholder instructions
4. Follow the established CSS patterns
5. Are documented with comments

## Resources

- [ATS Resume Scanning Guide](https://www.jobscan.co/ats-resume-guide)
- [HTML Resume Best Practices](https://www.w3.org/Style/Examples/007/print.en.html)
- Common ATS Systems: Taleo, Workday, Greenhouse, Lever

## License

[Choose appropriate license]

## Contributors

- Sylvia Maina - sylviahmaina6@gmail.com
- John Gitau Mwangi - mwangijohngitau1@gmail.com

---

**Remember:** The goal is to create resumes that pass ATS screening AND impress human recruiters. Balance is key!
