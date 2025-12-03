# Introduction to HedgeDoc
## What is HedgeDoc?

HedgeDoc is a real-time collaborative markdown editor that allows multiple users to work on the same document simultaneously through a web browser. Unlike traditional word processors, HedgeDoc uses markdown syntax for formatting, making it ideal for technical writing, documentation, and content that will eventually be published on platforms like GitHub Pages.

Key features include:
- Live collaboration - See changes from other editors in real-time, similar to Google Docs
- Markdown support - Write using simple markdown syntax with a side-by-side preview
- Version history - Track changes and revert to previous versions if needed
- Export options - Download documents as markdown, PDF, or HTML
- Self-hosted - Runs on institutional servers, keeping content secure and under local control

## What is Markdown?

Markdown is a lightweight markup language that uses simple, readable symbols to format text. Created in 2004, it was designed to be easy to write and easy to read, even in its raw form. Instead of clicking formatting buttons or writing complex HTML code, you use intuitive characters like # for headings, ** for bold text, and * for italics.

### Basic Markdown Examples

 ```markdown
    # This is a heading
    ## This is a subheading

    **This text is bold**
    *This text is italic*

    - Bullet point one
    - Bullet point two

    [Link text](https://example.com)
 ```


## Why Use Markdown for Portfolios? 

- **Portability** - Markdown files are plain text, so they work across any platform, editor, or operating system. You're never locked into proprietary software.

- **GitHub integration** - GitHub natively renders markdown files, making it the standard format for README files, documentation, and GitHub Pages sites. Your portfolio content flows seamlessly from editing to publication.

- **Version control friendly** - Because markdown is plain text, Git can easily track changes, show differences between versions, and merge contributions from multiple people.

- **Focus on content** - Markdown's simplicity keeps you focused on writing rather than fussing with formatting. The syntax is minimal and doesn't interrupt your thought process.

- **Future-proof** - Plain text files will always be readable. Unlike Word documents or other proprietary formats, markdown won't become obsolete or require special software to open decades from now.

- **Professional standard** - Markdown is widely used in technical fields, from software documentation to academic writing. Learning it builds a transferable skill for your career.

# Headers
Headers create a visual hierarchy in your document, helping readers quickly scan and navigate your content. They break up large blocks of text into organized sections, making your portfolio easier to read and more professional-looking.

Use larger headers (# or ##) for main sections like "About Me" or "Projects," and smaller headers (### or ####) for subsections within those areas. This structure also helps screen readers and search engines understand how your content is organized, improving accessibility and discoverability.

Use "#" followed by a space to create a new Header.

 ```markdown
    # Header 1 --> Largest
    ## Header 2 --> Medium
    ### Header 3 --> Smaller
 ```   
 
# Text Formatting

Markdown provides simple ways to emphasize and style your text, helping you highlight important information and improve readability.

## Bold Text

 ```markdown
    **text** or __text__
 ```
 
Example: 
**This text is bold**, __This text is also bold__

Use bold text to emphasize key points, important terms, or headings within paragraphs. Bold draws the reader's eye to critical information and helps them identify the most significant parts of your content at a glance.

## Italic Text
 ```markdown
    *text* or _text_
 ```
 
Example: 
*This text is italicized*, _This text is also italicized_

Italics provide subtle emphasis, often used for titles of works, technical terms when first introduced, or to add slight stress to specific words. It's less aggressive than bold but still helps certain text stand out.

## Bold and Italic Combined
 ```markdown
    ***text*** or ___text___
 ```
 
Example: 
***This text is both bold and italicized***, ___This text is also both bold and italicized___

Combining both creates maximum emphasis. Use this sparingly for only the most critical information - overuse diminishes its impact and makes your document look cluttered.

## Strikethrough
 ```markdown
    ~~text~~
 ```
 
Example:
~~This text has been struck through~~

Strikethrough shows deleted or outdated information while keeping it visible. This is useful when updating content to show what's changed, or in collaborative editing to suggest removals without completely erasing text.
    

# Lists

Lists help organize information into clear, scannable chunks that are easier for readers to process than long paragraphs. They're essential for presenting multiple items, steps, or ideas in a structured way.

## Unordered Lists (Bullet Points)
 ```markdown
    - item or * item
 ```
 
Example: 
- This is a bullet point
* This is also a bullet point

Use unordered lists when the sequence doesn't matter - like listing your skills, features of a project, or items in a collection. Bullet points signal to readers that these items are all equally important and can be read in any order.

## Ordered Lists (Numbered)
 ```markdown
    1. item 
    2. item
    3. item
```

Example: 
1. First Item
2. Second Item
3. Third Item

Use numbered lists when order or sequence matters - like tutorial steps, ranking items by priority, or showing a chronological timeline. Numbers help readers follow a specific progression and make it easy to reference particular items ("as mentioned in step 3...").

## Nested Lists

 ```markdown
    Indent with spaces or tabs before the list marker
 ```
    
Example:

1. This is a numbered list
    2. This is also a numbered list but it is nested in the one above 
* This is a bullet point
    1. This is a numbered list nested in that bullet point, this can be done with a bullet point inside a numbered list as well

Nested lists create subcategories or sub-steps within your main points, allowing you to show hierarchical relationships. This helps break complex information into manageable layers - for example, listing your projects with specific technologies or achievements under each one.

# Links

Links are essential for portfolios, allowing you to connect readers to your projects, GitHub repositories, social profiles, and external resources. They transform your portfolio from a static document into an interactive gateway to your work.

## Basic Link

 ```markdown
    [link text](URL)
 ```
    
Example: 
[My Github Profile](https://tinyurl.com/yu4ry6pm)

The link text (in brackets) is what readers see and click on. Make it descriptive and meaningful - instead of "click here", use text that explains where the link goes, like "View Project Repository" or "LinkedIn Profile".

## Link with Title (Tooltip)

 ```markdown
    [Link text](URL "Title text")
 ```
Example:
[Portfolio Project](https://tinyurl.com/yu4ry6pm "Definitely not a Rick Roll video")

The title appears when users hover over the link, providing additional context. This is helpful for giving readers a preview of what they'll find before they click.

## Direct URL Link

 ```markdown
    <URL>
 ```
 
Example:
<https://tinyurl.com/yu4ry6pm>

Wrapping a URL in angles brackets makes it automatically clickable. Use this for displaying the actual URL when that's important, rather than hiding it behind link text.

## Why Links Matter in Portfolios

Links let you demonstrate your work without cluttering your portfolio with screenshots or long descriptions. They provide evidence of skills, connect recruiters directly to your code, and help build your professional network by linking to your social profiles and collaborations.

# Code Formatting

Code formatting is crucial for technical portfolios, allowing you to display commands, code snippets, and programming examples in a clear, readable way that's visually distinct from regular text.

## Inline Code

 ```markdown
    `code`
 ```
 
Example: 
`git commit -m "Initial commit"`

Use inline code for short commands, function names, file paths, or variable names within a sentence. This helps readers immediately identify technical terms and distinguish them from regular text. For example: "Use the `cd` command to navigate directories"

## Code Blocks

Code blocks display code or commands in a gray box with monospace font.

To create a code block, indent your text with a Tab or 4 spaces.

Example:
    
    echo "This is an example of a code block"
    print("This is another example but in python")

You can also create a code block with 3 backticks before and after your code.

 ```markdown
    
    ```language
    code here
    ``` (close with three backticks)
 ```
    
Example:

```python
for i in example:
    print("This is an example")
```

Code blocks are essential for displaying multi-line code snippets, scripts, or configuration files. They preserve formatting, indentation, and line breaks, making your code readable and copy-pasteable.

Use code blocks when showing:
- Terminal commands
- Code snippets
- Configuration examples

### Syntax Highlighting

Adding a language name after the opening backticks (like `python`, `javascript`, `bash`) enables syntax highlighting, which color-codes different parts of the code. This dramatically improves readability and helps viewers quickly understand the code's structure.

### Why Code Formatting Matters

Proper code formatting demonstrates professionalism and technical literacy. It makes your portfolio easier to read for recruiters and fellow developers, shows attention to detail, and ensures that anyone reviewing your work can quickly understand and even test your code examples.

# Images 

Images bring your portfolio to life by showing project screenshots, diagrams, logos, and visual demonstrations of your work. They provide immediate visual proof of your accomplishments and make your portfolio more engaging.

## Basic Image

 ```markdown
    ![Alt text](image-url)
 ```
Example: 

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

The alt text (in brackets) describes the image for accessibility and appears if the image fails to load. Always write meaningful alt text that explains what the image shows. This helps visually impaired users and improves SEO (Search Engine Optimization;  the practice of making your content more discoverable by search engines)
-    When you optimize for SEO, you're helping search engines understand what your content is about so they can show it to people searching for relevant topics.
    

## Image with Title (Tooltip)

 ```markdown
    ![Alt text](image-url "title text")
 ```
    
Example: 

![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png "The GitHub Octocat logo")

The title text appears when users hover over the image, providing additional context or details about what they're viewing.

## Using Local Images

 ```markdown
    ![Alt text](./path/to/image.png)
 ```

Example:

![My Project Screenshot](./images/project-demo.png)

Command used:

```markdown=
![My Project Screenshot](./images/project-demo.png)
```

***NOTICE***
***The image above didn't load because this HedgeDoc file is not stored in a repository with an `images` folder or a `project-demo.png` file. Local image paths only work when the markdown file and the image are both saved in the same repository structure. When you create your actual portfolio on GitHub with proper folder organization, this syntax will work correctly.***

For images stored in your repository, use relative paths. This keeps your images with your project and ensures they'll always load even if external hosting services go down.

## Why Images Matter in Portfolios

Images provide visual evidence of your work and break up text-heavy content. Screenshots of completed projects, architecture diagrams, or UI designs give recruiters immediate insight into your capabilities. They're especially important for demonstrating hands-on technical projects where "showing" is more powerful than "telling".


## Best Practices for Portfolio Markdown

-    **Keep it simple** - Don't over-format your content. Clean, readable text beats fancy formatting that distracts from your actual accomplishments.
-    **Consistency matters** - Pick a style (like using `*` or `-` for bullets) and stick with it throughout your entire portfolio. This looks more professional.
-    **Organize with headings** - Use a logical hierarchy. Your name might be H1 (`#`), major sections like "Projects" are H2 (``##``), and individual projects are H3 (`###`).
-    **Proofread everything** - Typos in a technical portfolio suggest carelessness. Use spell check and have someone review your content before publishing.
-    **Keep URLs updated** - Regularly check that your links still work. Broken links to your projects make a bad impression on recruiters.
-    **Write for humans first** - While markdown is technical, your content should be conversational and clear. You're telling your story, not writing a manual.

## Common Mistakes to Avoid

-    Forgetting to close code blocks with three backticks 
-    Not adding alt text to images (breaks accessibility)
-    Using generic link text like "click here" instead of descriptive text
-    Over-nesting lists (more than 2-3 levels gets confusing)
-    Mixing heading levels inconsistently (jumping from H1 to H4)

