# This is a sample MARKDOWN file

Since most of the website constructor uses markdown pages as input, we require the CSST simulation members to provide markdown documents describing their data products.  

Here is a simple instruction for writing markdown files.
Also see [Markdown Guide](https://www.markdownguide.org/basic-syntax/).  
We recommend to use [Visual Studio Code](https://code.visualstudio.com/) to write and preview markdown files.

# Headings
This is samples for different level headings.

# Level 1 Heading

## Level 2 Heading

### Level 3 Heading

#### Level 4 Heading

##### Level 5 Heading

###### Level 6 Heading

Note that there is a blank between number signs \# and the contents.  
Level 1 heading will be followed by a horizontal line automatically.  
It's better to put a blank line before and after the headings.  

# Paragraph

A blank line is a sign for different paragraphs.  Between paragraphs, the vertical blank space is slightly larger.

Just a `<enter>` in the line end, the contents will look continous, like this.
If you want to break the line manually, type two or more blanks in the end of line.  
Like this.

# Fonts

Single star \*content\* for *Italic*,  
double stars \*\*content\*\* for **Bold**,  
triple stars \*\*\*content\*\*\* for ***Bold Italic***.  
To denote a phrase as code, enclose it in backticks \`content\`. `a=1`.  
Quick mail and link, use \<content\>, <https://www.baidu.com> or <yuyu22@sjtu.edu.cn>.  
To display a literal character which is itself a markdown syntax, add a backslash \\ before the character.

# Links

To create a link, enclose the link text in brackets (e.g., \[baidu\]) and then follow it immediately with the URL in parentheses (e.g., https://baidu.com).  
This will look like this, [baidu](https://www.baidu.com)

## Formatting Links

*[baidu.com](https://www.baidu.com)*,
**[baidu.com](https://www.baidu.com)**,
***[baidu.com](https://www.baidu.com)***.

# Lists

List is automatic
1. Content 1
2. Content 2  
    1. subcontent1
    2. subcontent2
       1. aaa
       2. bbb

This is unordered list.
- aaa
- bbb
    - aa
       - ddd 

# Tables

Use \| and \- for making tables.

| col1 | col2 | col3 |
| --- | --- | --- |
| text1 | text2 | text3 |

# Blocks

## Text blocks

This is a block.  Use \> for a block.
> aaaa
>
> end of block

Block can be nested.  Use \>\> for level 2 block.
> Level 1
>> Level 2
>> You can use **f***on****ts*** in blocks.

## Block with Styles

Use \`\`\` for blocks with style and specify the style afterward.
```warning
This is a warning block.  Although it looks a normal block in most markdown environment, it shows with style on webpage.  
Valid type includes warning, note, tip.
```

## Code blocks

You can also use block to show programing codes with highlights.
```fortran
program a
implicit none
real(4)::a=1.0
! Note that not all the syntax can be correctly recongized.
end program a
```

# Horizontal lines
Use \*\*\*, \-\-\-, or \_\_\_ (triple stars, minus signs, or underscores) to create horizontal lines.
***
---
___
Note that horizontal lines will not show up in some webpage environment.  

# Images
To add an image, add an exclamation mark \!, followed by alt text in brackets \[\], and the path or URL to the image asset in parentheses\(\). You can optionally add a title in quotation marks after the path or URL.
```
![This is alt text!](/directories/to/the/image/file.jpg "This is title for the image")
```
This is an example.  
![Show this if the image is broken!](https://blog.arxiv.org/files/2021/02/arxiv-logo.svg "arxiv LOGO")


