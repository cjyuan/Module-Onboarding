## PR Guide
  - Read the [PR Guide](https://programming.codeyourfuture.io/guides/reviewing/trainee-pr-guide/) to find out how
    to prepare a PR, use labels, and respond to reviewer's feedback.

## General Feedback for PRs in Module Onboarding

### Is the PR Description correctly formatted in Markdown syntax?

- Do the checked checkboxes look like this?
   - [x] I have tested my changes

- Is "Changelist" properly formatted as a level 2 header (so that it appears in larger font)?

Suggestion: If you are new to Markdown, you may find this [Quickstart for writing on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github) article useful.

### Ensure our HTML/CSS code is error free

Keeping our HTML and CSS code **validated** ensures compatibility, accessibility, easier maintenance, and 
a consistent user experience across browsers and devices.

Have you used to following services to validate your HTML and CSS code?
- HTML - [W3C Markup Validation](https://validator.w3.org/)
- CSS - [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
  - Note: This service does not seem work well with nested CSS selectors or variables.
    If this service does not work for you, try using an AI tool instead.

### Code Indentation

**Code indentation** is important because it makes our code easier to read, understand, and maintain. 
It helps clearly show the structure, especially in nested elements, reducing mistakes and improving collaboration.

Is your code properly indented?

VSCode has a built-in [Format Document](https://code.visualstudio.com/docs/editing/codebasics#_formatting) function
that can help us auto-indent our code.

### Using AI to Review Your HTML and CSS Code

AI can act like a helpful reviewer for your code, giving you feedback and suggestions to make it better.
It won’t replace validators or your own skills, but it can highlight issues you might miss and explain how to fix them.
By letting AI handle small or routine checks, mentors can focus on deeper improvements such as design, usability, and 
best practices.

#### How to use AI to review your code:
1. **Copy and paste your code into the AI** and ask questions like:
    - "Is my HTML valid?"
    - "Can you check if my CSS is correct?"
    - "Can you check for typo and consistency in my code?"
    - "How can I make my HTML more accessible?"
    - "Can you suggest possible improvement?"
2. **Read the feedback critically** – decide which suggestions to accept. 
    - You should only accept the suggestions if you understand what they mean.
3. **Apply changes step by step** so you can see the effect of each fix.  
4. **Validate with W3C validators** after making changes to ensure standards compliance.
5. **Learn from patterns**. Notice what kinds of mistakes AI points out, and work on avoiding them in future projects.

Using AI is **not cheating**. You can accept AI suggestions, but only if you understand them well enough to explain the change.
Once you can do that, the learning truly becomes yours.

---

## General Feedback for Wireframe PR

### Does your page layout match the wireframe?
<img src="Wireframe/wireframe.png" width="640" alt="The wireframe image in the Wireframe exercise">

When a wireframe is provided, our implementation should closely reflect its appearance and layout to ensure consistency with 
design expectations. The main purpose of implementing a wireframe is to translate structure and functionality, not final visual 
design. Visual design is usually handled by UI/graphic designers after the wireframe phase. So for examples, in your implementation:
- Are the PAGE TITLE and the SHORT DESCRIPTION beneath it centered horizontally on the page?
- Do all artiles have a border?
- Do the images in the article spans the full width of their respective articles?
- Do the images in articles 2 and 3 have the same height?
- Are the ARTICLE TITLE, ARTICLE SUMMARY, and the README link left aligned within each article?
- Do the left border of articles 1 and 2 align?
- Do the right border of articles 1 and 3 align?
- Do articles 2 and 3 have the same width?
- Do the README links all have a border?

### Is the footer **fixed** at the bottom of the **viewport**?
  - What does "fixed" mean?
  - What does "viewport" mean?

Suggestion: Use an AI tool to find out what this requirement mean.
