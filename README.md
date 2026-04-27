# 📘 Markdown Notes (Quick Guide)

---

# 01. Headings

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

## 👉 Output:

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

## <br><br>

# 02. Text Styling

```
**Bold text**
*Italic text*
~~Strikethrough~~
```

## 👉 Output:

**Bold text** <br>
_Italic text_ <br>
~~Strikethrough~~
<br><br>

# 03. Lists

## A. UnOrder List:

```
- Item 1
- Item 2
  - Sub item
```

### 👉 Output:

- Item 1
- Item 2
  - Sub item

## B. Order list

```
1. First
2. Second
3. Third
```

### 👉 Output:

1. First
2. Second
3. Third
   <br><br>

# 04. Links & Images

use html img tag for resizing height & width

```
[Google](https://google.com)

![Image](https://avatars.githubusercontent.com/5x30pm)
```

### 👉 Output:

[Google](https://google.com)

<img src="https://avatars.githubusercontent.com/5x30pm" height="50px" width="50px">
<br><br>

# 05. Code

## A. Inline-code

```
`<img src="#" alt="img.png">`
```

### 👉 Output:

\<img src="#" alt="img.png">

## B. Block code

first write the (\```) then write language name of code  
now write code and give (\```) in last

Like this:

\```python  
 print("hello world")  
 \```

### 👉 Output:

print("hello World")

<br><br>

# 06. Table

```
| Name   | Age |
| ------ | --- |
| Shiv   | 15  |
| Ranjan | 28  |
| Kumar  | 95  |

```

## Alignment in table

```
:---                                        //→ left
:---:                                       //→ center
---:                                        //→ right
```

### 👉 Output:

| Name   | Age |
| ------ | --- |
| Shiv   | 15  |
| Ranjan | 28  |
| Kumar  | 95  |

<br><br>

# 07. Blockquote

```
> This is a Shiv
```

### 👉 Output:

> This is a Shiv
> <br><br>

# 08. Horizontal line

```
---
```

<br><br>

### 👉 Output:

---

# 09. Checklist

```
- [x] Task 1
- [ ] Task 2
```

- [x] Task 1
- [ ] Task 2
      <br><br>

# 10. Line break (next line me space)

👉 Give Two spaces + Enter:

```
line 1
line 2
```

### 👉 Output:

line 1  
line 2
<br><br>

# 11. More Gap need (use Html tag)

```
&nbsp;                  // for single space
&nbsp;&nbsp;            // for two space
<br>                    // for brak the line
```

<br><br>

# 12. Alignment Item (text, Paragraph, image .....)

You have to use html. like this

```
<p align="center">This is center.</p>
<p align="left"> This is left.</p>            // defalt left hi hota hai
<p align="right">This is right.</p>
```

### 👉 Output:

<p align="center">This is center.</p>
 <p align="left"> This is left.</p>            
 <p align="right">This is right.</p>
 
   
<br><br>

# 13. Highlight text (work in some cases)

```
==Highlighted text==
```

### 👉 Output:

==Highlighted text==  
<br><br>

# 14. Superscript / Subscript

```
X<sup>2</sup>
H<sub>2</sub>O
```

### 👉 Output:

X<sup>2</sup>  
H<sub>2</sub>O
<br><br>

# 15. Collapsible Section

```
<details>
<summary>Click to expand</summary>

Hidden content here

</details>
```

### 👉 Output:

<details>
<summary>Click to expand</summary>

Hidden content here

</details>
<br><br>

# 16. Escaping characters

```
\*Not italic\*
```

### 👉 Output:

\*Not italic\*
<br><br>

# 17. Emojis 😄

```
:smile:
:rocket:
:fire:
```

### 👉 Output:

:smile: :rocket: :fire:
<br><br>

<p align="right">Thanks for visiting Markdown blog &hearts;</p>
