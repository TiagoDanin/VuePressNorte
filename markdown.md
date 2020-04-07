<!--https://gist.githubusercontent.com/jkmosdev/7ea725bcf45fb62c030ba5e9a8d69e90/raw/23989a9c26c6bfd494c4a71d47597b556f0c014b/Github%2520Markdowns.md-->

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6	


---

Paragraph
text `Inline Code` text		
~~Mistaken text.~~	
*Italics*	
**Bold**	

---

Tasks
- [ ] a task list item
- [ ] list syntax required
- [ ] normal **formatting**
- [ ] incomplete
- [x] completed

---

Code Blocks

    4 space indention
    makes full-width
    standard code blocks

```js
var now = new Date();

var days = new Array('Sunday','Monday','Tuesday','Wednesday','Thursday','Friday','Saturday');

var months = new Array('January','February','March','April','May','June','July','August','September','October','November','December');

var date = ((now.getDate()<10) ? "0" : "")+ now.getDate();

function fourdigits(number)	{
	return (number < 1000) ? number + 1900 : number;
								}
today =  days[now.getDay()] + ", " +
         months[now.getMonth()] + " " +
         date + ", " +
         (fourdigits(now.getYear())) ;

document.write(today);
```

```css
#sc_drag_area {
  height:100px;
  left:150px;
  position: absolute;
  top:100px;
  width:250px;
  z-index: 9999;
}
```

---

* List item one
* List item two
    * A nested item

---

1. Number list item one		
	1.1. A nested item
2. Number list item two
3. Number list item three

---

> Quote
> 
> Second line Quote

---

Standard link =  http://ghost.org	
[Custom Text Link](http://ghost.org)

---

![Image](https://vuepress.vuejs.org/architecture.png)

---

Table

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |