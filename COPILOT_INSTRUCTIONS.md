# Copilot Instructions for VocabularyProject

## Project Overview
**Project Name:** VocabularyProject  
**Repository Owner:** tatsianakibin  
**Current Branch:** main  
**Project Type:** Educational vocabulary resource for Business English courses  
**Primary Focus:** HTML-based vocabulary learning materials for B1+ level English students

## Repository Structure
```
VocabularyProject/
├── BusinessEnglish-B1-Plus.html    # B1+ level business vocabulary
├── BusinessEnglish-B2-Plus.html    # B2+ level business vocabulary
├── index.html                       # Main landing page
└── COPILOT_INSTRUCTIONS.md         # This file
```

## Content Overview

### BusinessEnglish-B1-Plus.html
- **Units Covered:** 7 units (1, 2, 3, 4, 6, 7)
- **Content Structure:** Vocabulary items with word, phonetic transcription, definition, and examples
- **Features:** 
  - Styled vocabulary cards with hover effects
  - Linked Quizlet flashcards for practice
  - Organized by business topics (leadership, communication, presentations, employment, strategy, investment, behavior)
  - Interactive table of contents with anchor links
  - Gradient background and modern CSS styling

### BusinessEnglish-B2-Plus.html
- Similar structure to B1+ but for advanced learners

### index.html
- Main landing page for the vocabulary project

## Working Guidelines for Copilot

### 1. File Modifications
When editing HTML files:
- **Preserve Structure:** Maintain the semantic HTML structure (header, content divs, units, vocab-items)
- **CSS Consistency:** Use existing color scheme (primary: #667eea, secondary: #764ba2, accent: #48bb78)
- **Formatting:** Maintain consistent indentation (4 spaces) and line spacing
- **Vocabulary Items:** Follow the established format:
  ```html
  <div class="vocab-item">
      <div class="word">Word/Phrase</div>
      <div class="transcription">/phonetic/</div>
      <div class="definition">Clear definition</div>
      <div class="example">Example sentence</div>
  </div>
  ```

### 2. Adding New Content
When adding new vocabulary items:
- Include British English phonetic transcription in IPA format
- Provide clear, concise definitions suitable for B1/B2 learners
- Include business-relevant example sentences
- Ensure each item includes: word, transcription, definition, and example
- Maintain alphabetical or thematic ordering within sections

### 3. Quizlet Links
- Format: `https://quizlet.com/[ID]/[name]/?[params]`
- Always open links in new tabs (`target="_blank"`)
- Style links consistently with project colors (no underline, color: #667eea, bold font)

### 4. Git Workflow
**Always follow these steps for commits:**

1. **Stage changes:**
   ```bash
   git add <filename>
   ```

2. **Create descriptive commit messages:**
   - Format: `[TYPE] Brief description`
   - Types: `[ADD]`, `[UPDATE]`, `[FIX]`, `[REFACTOR]`, `[DOCS]`
   - Examples:
     - `[ADD] Add Unit 5 vocabulary to B1+ course`
     - `[UPDATE] Improve styling for vocab items`
     - `[FIX] Correct phonetic transcription in Unit 3`

3. **Commit with message:**
   ```bash
   git commit -m "Your commit message"
   ```

4. **Push to remote:**
   ```bash
   git push origin main
   ```

### 5. HTML/CSS Best Practices
- **Color Palette:** 
  - Primary: #667eea (purple-blue)
  - Secondary: #764ba2 (dark purple)
  - Accent: #48bb78 (green) - for examples
  - Text: #2d3748 (dark gray)
  - Background: #f8f9fa (light gray)
  
- **Typography:**
  - Font Family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
  - Headings: 2em for unit titles, 1.5em for subsections
  - Body text: 1.05em for definitions, 1em for examples

- **Spacing:**
  - Unit margins: 50px bottom
  - Vocab item margins: 20px bottom
  - Padding: 25px for vocab items, 40px for sections

### 6. Content Quality Standards
- **Definitions:** Should be clear and appropriate for B1/B2 level (not overly technical)
- **Examples:** Should show real business context usage
- **Transcription:** Must be accurate IPA format
- **Consistency:** Maintain parallel structure across all vocabulary items
- **Links:** Verify Quizlet links are functional and point to correct flashcard sets

### 7. Testing & Validation
Before committing changes:
- Verify HTML syntax is valid
- Check that all links work correctly
- Ensure CSS classes are properly applied
- Test responsive design (should work on desktop, tablet, mobile)
- Verify all Quizlet links open in new tabs

### 8. Common Tasks

#### Adding a new vocabulary item:
1. Locate the appropriate unit section in the HTML file
2. Add a new `<div class="vocab-item">` block
3. Include: word, transcription, definition, example
4. Maintain consistent formatting and styling
5. Commit with: `[ADD] Add '[word]' to Unit [X]`

#### Updating existing content:
1. Find the specific vocab item
2. Update only the necessary parts (definition, example, etc.)
3. Commit with: `[UPDATE] Improve '[word]' definition in Unit [X]`

#### Adding new Quizlet links:
1. Find the Quizlet practice section at the end of each unit
2. Add link following the established format
3. Ensure link opens in new tab
4. Commit with: `[UPDATE] Add Quizlet link for Unit [X]`

#### Fixing errors:
1. Identify the error (typo, wrong transcription, broken link, etc.)
2. Make the correction
3. Commit with: `[FIX] Correct [description] in Unit [X]`

### 9. Communication Preferences
- Use clear, descriptive commit messages
- When making multiple changes, consider breaking them into separate commits for clarity
- Document significant structural changes in commit messages
- Keep related changes together in a single commit

### 10. Accessibility & Performance
- Ensure proper heading hierarchy (h1 → h2 → h3)
- Use semantic HTML elements appropriately
- Maintain good color contrast for readability
- Optimize image use (minimize file sizes)
- Keep CSS and HTML clean and efficient

## Project Goals
- Provide comprehensive business English vocabulary resources
- Support B1+ and B2+ level learners
- Integrate with Quizlet for interactive practice
- Maintain consistent, professional design
- Ensure easy navigation and accessibility

## Questions or Clarifications
If you need to make changes beyond these guidelines, ask for clarification before proceeding. Always prioritize:
1. **User experience** - Easy to read and navigate
2. **Content accuracy** - Correct definitions, transcriptions, and examples
3. **Consistency** - Uniform structure and styling across all files
4. **Maintainability** - Clean code that's easy to update in the future
