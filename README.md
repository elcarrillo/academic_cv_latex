# README for CV LaTeX Template


## Project Overview


This LaTeX project provides a customizable and user-friendly CV template, designed to present professional and academic achievements in a clean, organized format. The template includes sections for education, research experience, publications, field experience, teaching, and more. 

The project uses the `article` document class for enhanced customization and flexibility. While specialized CV classes (e.g., `moderncv`) exist, the `article` class was chosen to allow greater control over layout and formatting options.

## Features
- **Custom Header and Footer**: Displays the page number and total number of pages (e.g., `1/4`).
- **Responsive Tables**: Uses `tabularx` to automatically adjust column widths.
- **Custom Section Titles**: Defines different styles for sections, subsections, and sub-subsections.
- **Hanging Indents**: Applied to publication sections for citation-style formatting and neat alignment.
- **Icons**: Uses `fontawesome` for social media icons (e.g., email, GitHub).
- **Line Spacing**: Customized for readability.
- **Hyperlinks**: URLs are clickable, and internal links are hidden for neat page navigation.

---

## File Structure

- `main.tex`: The main LaTeX file that builds the CV.
- `README.md`: (this file) provides an overview of the project and instructions.

---

## Required Packages

Here’s a brief explanation of the LaTeX packages used in this template:

- `geometry`: Controls page layout and margins.
- `titlesec`: Customizes section titles (size, color, underline).
- `setspace`: Controls line spacing.
- `enumitem`: Manages custom list formatting.
- `xcolor`: Adds custom color support.
- `fancyhdr`: Configures headers and footers.
- `hyperref`: Enables clickable URLs and links.
- `fontawesome`: Adds social media icons (GitHub, email, etc.).
- `tabularx`: Creates tables with auto-sizing columns.
- `hanging`: Enables hanging indents for citation formatting.
- `helvet`: Uses Helvetica font for a modern sans-serif look.
- `lastpage`: Allows referencing the last page for page counts.

---

## Usage Instructions

1. Clone or download this project.
2. Open the `.tex` file and update the personal information (name, contact details) in the document header.
3. Modify each section according to your background.
4. Compile the document using your preferred LaTeX editor (Overleaf, TeXShop, etc.).
5. Export the final CV as a PDF.

---

## Example: Adding a New Section

You can easily add new sections using the following structure:

```latex
\section*{New Section Title}
\begin{tabularx}{\textwidth}{>{\raggedright\arraybackslash}p{2.5cm} X}
Year & \textbf{Role}, Organization, Location \\
     & Description of role or project.
\end{tabularx}
```


## Future Improvements

1. **Multi-page Support**: Test the template with longer CVs and adjust spacing to maintain consistency across multiple pages.
2. **Mobile Compatibility**: Optimize the digital version of the CV for viewing on smaller screens, ensuring it displays well on mobile devices.

## Author

**Edgar Carrillo**

Feel free to reach out if you have any questions or suggestions for improvement!

**Email**: [elcar@uoregon.edu](mailto:elcar@uoregon.edu)


## License

This CV template is open-source. You are free to use, modify, and share it for personal or professional purposes.
