#General Styles

All code should follow the rules in this guide unless otherwise noted in a language specific guide. These rules are to help keep code readable and maintainable for future users.

##Naming

Create meaningful names for everything. Always favor longer, more descriptive names to short, abbreviated ones (common abbreviations like 'sum' are ok).

Use camelCase for all naming unless otherwise specified by a language.

Classes, interfaces and other similar objects should start with an uppercase letter and all other names (variables, methods, functions) should start with a lowercase letter.

Ex:

```
class Person {
  function getFirstName() {
    firstName = 'Joe';
  }
}
```

##Indentation/Whitespace

All line indentation must be 2 spaces, do not use tabs. You can change the defualts in your editor to do this automatically.

Do not leave trailing whitespaces at the end of lines.

Try not to exceed 80 characters per line as it makes it hard to read. An exception to this is URLs and other lines that cannot be broken up.

##Brackets

Open curly brackets on the same line and close them with the same indentation as the line on which they originated. Always start a new line after a curly brace, unless it is a `else` in a control flow statement. Leave a space between the statement and the opening curly bracket. Use one space between the statement and bracket.

Ex:

```
function foo() {
  bar = 1;
}
```

If brackets or braces are optional, always use them. Even if the statement can be represented on one line without brackets include them so it is easier to read.

##Comments

Inline comments are ok but should be kept short. For longer comments (describing functions, etc.) use block comments. Also make use of `TODO` to note what needs to be done later in the code.

Ex.

```
// TODO: this is a todo comment

// this is an inline comment

/*
 * This is a longer, multiline comment. It is useful for lots of text
 * that needs to be displayed.
 */
