# Markdown for Github :octocat: 
## Heading 
Heading is usually used for title of a topic or sub topic
#### Format :
```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
#### Output :
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Emphasis
#### Format :
```
Bold : **B** or __B__
Italic : *i* or _i_
Combined (partial) : **Bold and _Italic_** or __Bold and *Italic*__
Combiner (all) : ***Bold and Italic*** or ___Bold and Italic___
Strikethrough : ~~S~~
```
#### Output :
Bold : **B** or __B__\
Italic : *i* or _i_\
Combined (partial) : **Bold and _Italic_** or __Bold and *Italic*__
Combiner (all) : ***Bold and Italic*** or ___Bold and Italic___
Strikethrough : ~~S~~

## Quoting Text
If we want to quote a text we can use `>`.If we want to add quote inside another quote we can use `>>` .
#### Format :
```
> #### Mae West was said:
>> “You only live once, but if you do it right, once is enough.” 
```

#### Output :
> #### Mae West was said:
>> “You only live once, but if you do it right, once is enough.” 

## Quoting Code
It used for block a code. There are two ways to quote code. They are quote code inline with text and quote code with its own box. If we want to make quote inline with text we can use a single backticks, the code inside the backticks will be quoted.
#### Format :

```
`sudo` is a very useful command
```
#### Output :
`sudo` is a very useful command

In other hand,if we want to block code into a separate box, you can use triple backticks. The code inside the backticks will be quoted.
#### Format :
````
Basic batch command :
```
@echo off
echo Started : %time%
echo Finished : %time%
```
````

#### Output :
Basic batch command :
```
@echo off
echo Started : %time%
echo Finished : %time%
```

We also can use syntax highlighting for a programming language. 
#### Format :
````
```java
public class Main{
   public static void main (String [] args){
      System.out.println("Hello World");
   }
}
```
````

#### Output :
```java
public class Main{
   public static void main (String [] args){
      System.out.println("Hello World");
   }
}
```
## Links
We can create an inline link using by wrap the link text with the brackets `[text]` and wrap the url with the parentheses `(URL)`. 
#### Format :
```
[Writing on Github](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax#quoting-code) 
```

#### Output :
[Writing on Github](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax#quoting-code) 


## Image
#### Format :
```
Inline-style :
![github](https://img.icons8.com/office/2x/markdown.png)

Reference-style :
![github][logo]

[logo]: https://img.icons8.com/office/2x/markdown.png
```
#### Output :
Inline-style :
![github](https://img.icons8.com/office/2x/markdown.png)

Reference-style :
![github][logo]

[logo]: https://img.icons8.com/office/2x/markdown.png
## Lists
1) You can make an unordered list using `*` or `-`
#### Format :
```
* list 1
* list 2
- list 1 
- list 2
```

#### Output :
* list 1
* list 2
- list 1 
- list 2

2) You can make ordered lists using `1.`
#### Format :
```
1. list 1
1. list 2
1. list 3
```
#### Output :
1. list 1
1. list 2
1. list 3

3) Nested list,if we want to make nested list in github need to give attention on this format :
![](https://help.github.com/assets/images/help/writing/nested-list-alignment.png)\
You should put `1.` or `-` or `*` below the first letter of higher list. For example :
#### Example :
```
1. List 1 lvl 1
   - List 1 lvl 2
   - List 1 lvl 2 
1. List 2 lvl 1
   - List 2 lvl 2
     - List2 lvl 3
       1. List 2 lvl 4
- List 3 lvl 1
  - List 3 lvl 2
    1. List 3 lvl 2    
       - List 3 lvl 3
         1. List 3 lvl 4
```

##### Output :
1. List 1 lvl 1
   - List 1 lvl 2
   - List 1 lvl 2 
1. List 2 lvl 1
   - List 2 lvl 2
     - List2 lvl 3
       1. List 2 lvl 4
- List 3 lvl 1
  - List 3 lvl 2
    1. List 3 lvl 3    
       - List 3 lvl 4
         1. List 3 lvl 5

## Task List
To create a task list we can use `[ ]`. To mark it completed, use `[x]`.
#### Example :
```
- [x] Linux.md
- [x] Bash Scripting.md
- [ ] Markdown.md
```
#### Output
- [x] Linux.md
- [x] Bash Scripting.md
- [ ] Markdown.md

## Source
- https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax#section-links
- https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#images









