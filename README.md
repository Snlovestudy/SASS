# Tasks
## 1 What is Sass?
**Prompt Annswer:**
"
Sass (Syntactically Awesome Style Sheets) is a preprocessor scripting language that compiles to CSS. It adds features like variables, nesting, mixins, inheritance, and more, which make CSS more maintainable and easier to work with, especially for large projects.
"

## 2 How does nesting work in Sass?
**Prompt Annswer:**
" Nesting in Sass allows you to nest CSS selectors in a way that follows the HTML structure, making it easier to organize styles. Example:
.nav {
  background: #333;
  ul {
    margin: 0;
    li {
      display: inline-block;
      a {
        color: white;
      }
    }
  }
}

"

## 3 What is inheritance in Sass, and how is it achieved?
**Prompt Annswer:**
" Inheritance in Sass is achieved using the @extend directive, allowing one selector to inherit styles from another. This avoids code duplication and maintains consistency. Example:
.button {
  padding: 10px 20px;
  background: blue;
  color: white;
}
.primary-button {
  @extend .button;
  background: green;
}


"