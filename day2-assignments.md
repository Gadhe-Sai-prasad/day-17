# Day 2 Assignments: HTML5 & CSS3 Fundamentals
## Basic Elements & Styling Practice

### Assignment 1: Setup & Basic Structure

**Task 1: Development Environment Setup**
1. VS Code Installation:

   a. Go to code.visualstudio.com
   b. Download for your system (Windows/Mac)
   c. Install with all defaults checked


2. Install Extensions:

   a. Live Server


3. Create Project Structure:
  
   web-basics/
   ├── day2/
   │   ├── index.html
   │   ├── styles/
   │   │   └── style.css
  

### Assignment 2: HTML Elements Practice

**Task: Create a webpage (index.html) with following elements:**

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>HTML Elements Practice</title>
</head>
<body>
    <!-- 1. Headings Practice -->
    <h1>This is Heading 1</h1>
    <h2>This is Heading 2</h2>
    <h3>This is Heading 3</h3>
    <h4>This is Heading 4</h4>
    <h5>This is Heading 5</h5>
    <h6>This is Heading 6</h6>

    <!-- 2. Paragraph Practice -->
    <p>This is a normal paragraph. Add your own text here.</p>
    <p>This is another paragraph with <strong>bold text</strong> and <em>italic text</em>.</p>

    <!-- 3. Block Elements -->
    <div class="block-example">
        This is a block element (div)
    </div>

    <!-- 4. Inline Elements -->
    <span class="inline-example">This is inline</span>
    <span class="inline-example">This is also inline</span>
</body>
</html>


### Assignment 3: CSS Styling Practice

**Task 1: Inline CSS**
Add to your HTML:

<h1 style="color: blue; font-size: 24px;">Inline Styled Heading</h1>
<p style="background-color: yellow; padding: 10px;">Styled paragraph</p>


**Task 2: Internal CSS**
Add to your `<head>` section:

<style>
    h2 {
        color: green;
        font-family: Arial, sans-serif;
    }
    
    .block-example {
        background-color: lightgray;
        padding: 15px;
        margin: 10px;
        border: 2px solid black;
    }
    
    .inline-example {
        color: red;
        margin: 5px;
        padding: 5px;
        border: 1px solid red;
    }
</style>


**Task 3: External CSS**
Create `styles/style.css`:
css
/* Box Model Practice */
.box-model-demo {
    width: 200px;
    height: 100px;
    padding: 20px;
    margin: 15px;
    border: 5px solid blue;
    background-color: lightblue;
}

/* Block vs Inline Practice */
.block-element {
    display: block;
    background-color: #ffeb3b;
    margin: 10px 0;
    padding: 10px;
}

.inline-element {
    display: inline;
    background-color: #4caf50;
    color: white;
    padding: 5px;
}


### Assignment 4: Practical Implementation

**Task: Create a News Article Page**

html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>News Article</title>
    <link rel="stylesheet" href="styles/style.css">
    <style>
        /* Internal CSS for article specific styles */
        .article-container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .article-title {
            color: #2c3e50;
            font-size: 28px;
        }
        
        .article-meta {
            color: #7f8c8d;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="article-container">
        <h1 class="article-title">Your Article Title</h1>
        <p class="article-meta">Published on: January 6, 2025</p>
        
        <!-- Add article content with various HTML elements -->
        <div class="article-content">
            <p>First paragraph...</p>
            <h2>Subheading</h2>
            <p>More content...</p>
        </div>
    </div>
</body>
</html>

### Success Checklist ✅

1. Environment Setup:
   - [ ] VS Code installed
   - [ ] Extensions working
   - [ ] Project structure created

2. HTML Elements:
   - [ ] All headings used correctly
   - [ ] Paragraphs formatted properly
   - [ ] Block elements implemented
   - [ ] Inline elements implemented

3. CSS Implementation:
   - [ ] Inline CSS working
   - [ ] Internal CSS applied
   - [ ] External CSS linked
   - [ ] Box model demonstrated

### Practice Tasks 🎯

1. **Color Practice:**
   - Try different color formats (names)
   - Test background colors
   - Experiment with text colors

2. **Box Model Practice:**
   - Create boxes with different:
     - Padding values
     - Margin values
     - Border styles

3. **Display Property:**
   - Convert block to inline
   - Convert inline to block
   - Test inline-block

### Tips for Success 💡

1. **VS Code Tips:**
   - Use `! + Tab` for HTML boilerplate
   - Use `Alt + Shift + F` to format code
   - Use Live Server to see changes instantly

2. **Common Mistakes to Avoid:**
   - Don't forget HTML doctype
   - Close all tags properly
   - Link CSS files correctly
   - Check file paths carefully

3. **Best Practices:**
   - Keep code indented
   - Use meaningful class names
   - Comment your code
   - Test frequently

### Submission Requirements 📝

1. **Files to Submit:**
   - index.html
   - style.css
   - Screenshots of your pages

2. **Code Quality:**
   - Properly formatted
   - Well-commented
   - No errors in console

3. **Documentation:**
   - Brief explanation of your approach
   - Any challenges faced
   - How you solved problems