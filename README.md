# sample-markdown
sample repository


### Team INDIA
1. M.S.Dhoni
7. Virat Kohli
4. Rohit Sharma

* Pakistan
* Australia
* New zealand

### Punyam Anand Maheshwar

I'm from tirupati, INDIA. I'm a kind of person who is always intrested to learn new things and try to explore them. This intrest in me has motivated me and finally i'm here in masters to enrich my skills.
![mahesh_image](https://raw.githubusercontent.com/Maheshwarpa/sample-markdown/main/IMG20230124143235.jpg)

[PLease_click_me](IMG20230124143235.jpg)

***
### **Tourist Places**

The below table indicates country's which are good to visit and are few of the worlds most beautiful places one must make a look.
|# Name of the Country|# Recommendation Reason|# No of Days Spent|
| :---: | :---: | :---: |
| INDIA | To view its culture and heritage | LifeTime |
| UAE | To view futuristic projects | 30 Days |
| USA | To learn the latest Technology | 365 Days|
| CHINA | To watch their working culture and industrail units | 90 Days |
| AUSTRALIA | Especially for Kangaroo | 30 Days |

***
### **Pithy Quotes**

> Just believe in you, you can By *"Maheshwar Punyam Anand"*.

>  Trust no one, Kill anyone but be only one By *"Billa"*.

***
### Code Fencing

> SVG patterns scaling the way pattern is not cut off

Link for reference <https://stackoverflow.com/questions/61179458/svg-patterns-scaling-the-way-pattern-is-not-cut-off>

```
<svg width="100%" height="100%">
  
  <!-- Create mask that we'll use to define a slight gradient -->
  <mask maskUnits="userSpaceOnUse" id="fade">
    <!-- Here's that slight gradient -->
     	<linearGradient id="gradient" x1="0" y1="0" x2="0" y2="100%">
      <stop offset="0" style="stop-color: #FFFFFF"></stop>
      <stop offset="1" style="stop-color: #000000"></stop>
    </linearGradient>
    <!-- The canvas for our mask -->
    <rect fill="url(#gradient)" width="100%" height="100%"></rect>
  </mask>
    
  <!-- Let's define the pattern -->
  <!-- The width and height should be double the circle radius we plan to use -->
  <pattern id="pattern-circles" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
    <!-- Now let's draw the circle -->
    <!-- We're going to define the `fill` in the CSS for flexible use -->
    <circle mask="url(#fade)" cx="20" cy="20" r="20"></circle>
  </pattern>
  <!-- The canvas with our applied pattern -->
  <rect x="0" y="0" width="100%" height="100%" fill="url(#pattern-circles)"></rect>
  
</svg>

```

Code Snippet Link <https://css-tricks.com/snippets/svg/svg-patterns/>

