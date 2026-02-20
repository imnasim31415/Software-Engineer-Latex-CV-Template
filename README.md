# Software-Engineer-Latex-CV-Template

Professional Software Engineer resume built with LaTeX, featuring a clean, ATS-friendly design with modular structure for easy maintenance.

## 🏗️ Project Structure

```
.
├── main.tex                            # Main file (compile this)
├── preamble.tex                        # Document setup & packages
├── commands.tex                        # Custom LaTeX commands
├── header.tex                          # Contact information
├── experience.tex                      # Work experience
├── education.tex                       # Education
├── certifications.tex                  # Certifications
├── competitive_programming.tex         # CP achievements
├── skills.tex                          # Technical skills
├── projects.tex                        # Projects
├── .gitignore                          # Git ignore rules
└── README.md                           # This file
```

## 🚀 Quick Start

### Prerequisites
- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- Git

### Compile the Resume

#### Using pdflatex (Recommended)
```bash
pdflatex main.tex
```

#### Using latexmk
```bash
latexmk -pdf main.tex
```

#### Using Overleaf
1. Upload all `.tex` files to Overleaf
2. Set `main.tex` as the main document
3. Click "Recompile"

## 📝 Making Updates

### Update Contact Information
Edit `header.tex` to change phone, email, location, or social links.

### Add/Update Work Experience
Edit `experience.tex` and add new positions using the `\resumeSubheading` command:

```latex
\resumeSubheading
  {Job Title}{Start Date -- End Date}
  {Company Name}{}
  \resumeItemListStart
    \resumeItem{Description of responsibilities and achievements}
  \resumeItemListEnd
```

### Update Skills
Edit `skills.tex` to add new technologies or frameworks.

### Add Projects
Edit `projects.tex` to showcase new projects.

### Change Section Order
Modify the `\input{}` order in `main.tex`.

## 🔄 Version Control

### Semantic Versioning
This project follows [Semantic Versioning](https://semver.org/):
- **Major** (X.0.0): Complete resume redesign or major structural changes
- **Minor** (0.X.0): New sections, jobs, certifications, or significant content additions
- **Patch** (0.0.X): Minor updates, typo fixes, or small content tweaks

### Tagging Releases
```bash
# Create a new version tag
git tag -a v1.2.0 -m "Add new certification and update skills"

# Push tags to GitHub
git push origin --tags
```

### Example Workflow
```bash
# Make changes to your CV
git add .
git commit -m "feat: add RHCSA certification"

# Tag the version
git tag -a v1.1.0 -m "Added RHCSA certification"

# Push changes and tags
git push origin main
git push origin --tags
```

## 📋 Commit Message Convention

Following [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` New content (job, project, skill)
- `fix:` Corrections (typos, dates, links)
- `style:` Formatting changes (spacing, fonts)
- `docs:` Documentation updates
- `refactor:` Restructuring without content changes

**Examples:**
```bash
git commit -m "feat: add Junior Software Engineer position at DSi"
git commit -m "fix: correct CGPA from 3.95 to 3.86"
git commit -m "style: increase name font size in header"
git commit -m "docs: update README with compilation instructions"
```

## 🎨 Features

- ✅ **ATS-Friendly**: Machine-readable format for Applicant Tracking Systems
- ✅ **Modular Design**: Easy to maintain and update individual sections
- ✅ **One-Page**: Optimized to fit on a single page
- ✅ **Professional Layout**: Clean, modern design
- ✅ **Hyperlinked**: Clickable links for email, website, GitHub, LinkedIn
- ✅ **Version Controlled**: Track all changes with Git

## 🛠️ Customization

### Change Colors
Edit `preamble.tex` to modify the color scheme.

### Adjust Spacing
Modify spacing values in `commands.tex` for tighter or looser layouts.

### Font Styles
Uncomment font packages in `preamble.tex` for different typefaces.

## 📞 Contact

**Nasim Hossain**
- Email: [ping@nasimhossain.dev](mailto:ping@nasimhossain.dev)
- Website: [nasimhossain.dev](https://nasimhossain.dev)
- LinkedIn: [linkedin.com/in/imnasim31415](https://www.linkedin.com/in/imnasim31415/)
- GitHub: [github.com/imnasim31415](https://github.com/imnasim31415)
- Location: Rampura, Dhaka, Bangladesh
---

**Last Updated**: February 2025 | **Current Version**: v1.0.0
