# Markdown Syntax Github

## Declare headings
To create headers, add the pound/hash symbol (#) in front of your text. The number of pound symbols determines the header level.
```
#Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```

## Emphasize text
Using italics in text is as easy as surrounding the target text with single asterisks (*) or single underscores (_). Just be sure to close an emphasis with the same character with which you opened it. Be observant of how you combine the use of asterisks and underscores. Here are several examples:
```
This is *italic* text.
This is also _italic_ text.
```
> This is *italic* text. This is also _italic_ text.

Create bold text by using two asterisks (**) or two underscores (__).
```
This is **bold** text.
This is also __bold__ text.
```
> This is **bold** text. This is also __bold__ text.

You can also mix different emphases.
```
_This is **italic and bold** text_ using a single underscore for italic and double asterisks for bold.
__This is bold and *italic* text__ using double underscores for bold and single asterisks for italic.
```
> _This is **italic and bold** text_ using a single underscore for italic and double asterisks for bold.
>
> **This is bold and _italic_ text** using double underscores for bold and single asterisks for italic.

## Link to images and sites
Image and site links use a similar syntax.
```
![Link an image.](/learn/azure-devops/shared/media/mara.png)
```
```
[Link to Microsoft Training](/training)
```

## Make lists
You can define ordered or unordered lists. You can also define nested items through indentation.
- Ordered lists start with numbers.
- Unordered lists can use asterisks or dashes (-).
Here's the Markdown for an ordered list:
```
1. First
1. Second
1. Third
```
Result : 
> 1. First
> 2. Second
> 3. Third

Here's the Markdown for an unordered list:
```
- First
  - Nested
- Second
- Third
```
Result :
> - First
>   - Nested
> - Second
> - Third

## Build tables
You can construct tables using a combination of pipes (|) for column breaks and dashes (-) to designate the prior row as a header.
```
First|Second
-|-
1|2
3|4
```
Result : 
> First|Second
> -|-
> 1|2
> 3|4

## Quote text
You can create blockquotes using the greater than (>) character.
```
> This is quoted text.
```
> This is quoted text.

## Fill the gaps with inline HTML
If you come across an HTML scenario not supported by Markdown, you can use that HTML inline.
```
Here is a<br />line break
```
> Here is a<br />line break

## Work with code
Markdown provides default behavior for working with inline code blocks delimited by the backtick (`) character. When decorating text with this character, it's rendered as code.
```
This is `code`.
```
> This is `code`.

GFM extends this support with syntax highlighting for popular languages. Just specify the language as part of the first tick sequence.
```javascript
var first = 1;
var second = 2;
var sum = first + second;
```
> ```javascript
> var first = 1;
> var second = 2;
> var sum = first + second;
> ```

## Mention users and teams
```
@githubteacher
```
> @githubteacher

## Track task lists
You can create task lists within issues or pull requests using the following syntax. These can be helpful to track progress when used in the body of an issue or pull request.
```
- [x] First task
- [x] Second task
- [ ] Third task
```
> - [x] First task
> - [x] Second task
> - [ ] Third task

