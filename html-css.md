**# html & css**

------------------------------------------
**1- concept of responsive web design. How do you ensure a website is responsive across different devices and screen sizes**
*  Responsive web design ensures that a website adapts and displays properly on various devices and screen sizes.

------------------------------------------
**2- What are the advantages and disadvantages of using CSS preprocessors like Sass or Less**
* css preprocessors like SASS and LESS extend CSS with features such as variables, mixins, and nesting, making the code more 
  maintainable and efficient.
   
------------------------------------------
**3- What is the difference between CSS grid layout and CSS flexbox? When would you use one over the other**
  
------------------------------------------
**4- What are some techniques for optimizing website accessibility? How do you ensure your website is accessible to users with 
     disabilities**
  
------------------------------------------
**5- What is the purpose of CSS media queries. How can they be used to create responsive designs**
* media queries allow you to apply different styles based on the user's device characteristics, such as screen size, resolution, or 
   orientation.
  
------------------------------------------

**6- What are some best practices for optimizing SEO (Search Engine Optimization) in web development**
  
------------------------------------------
**7- What is box model**
* css box model describes how elements are displayed on a webpage. It consists of content, padding, border, and margin.
   
------------------------------------------
**8- inline vs inline-block**
  
------------------------------------------
**9- describe the positions and  absolute vs relative position, fixed vs sticky**
  
------------------------------------------
**10- How can you align a div at center**
  
------------------------------------------
**11- difference between svg vs canvas**
  
------------------------------------------
**12- pseudo-class**
  
------------------------------------------
**13- What is the difference between HTML and HTML5**
* HTML5 is the latest version of HTML and includes new elements, attributes, and APIs compared to the older HTML versions.
   
------------------------------------------
**14 difference between margin and padding**
  Padding is the space between the content and the border, while margin is the space between the border and surrounding elements.
  
------------------------------------------
**15- What is the significance of z-index**
   The `z-index` property is used to control the stacking order of elements. Elements with higher `z-index` values will be displayed above elements with lower values.
   
------------------------------------------
**16- specificity or precidance in css** 
  
------------------------------------------
**17- em vs rem units**
  
------------------------------------------

**18- Custom properties (variables)**
* we can define and use custom properties for easier them using and maintain.
  
```
:root{
--main-color:#0000
}
h1{
color: var(--main-color)
}
```

------------------------------------------

**19- empty for empty elements**
```
p:empty{
    display: none;
  }
```
------------------------------------------


**#20 Viewport units for responsive typography**
* Using viewport units(vw,vh vmin,vmax) we can set font sizes responsive to the viewport size.
```  
h1{
    font-size: 5vw;
  }
```  

------------------------------------------


**# smooth scrolling on your website**
```
html{
    scroll-behavior: smooth;
  }
```
------------------------------------------

**# Object-fit property for image control**
```
img{
    width: 100px; 
    height: 100px;
    object-fit: cover;
  }
```

------------------------------------------

 **# :not() pseudo class** 
```
 
li:not(.one){
        font-stlye: italic;
    }
```

------------------------------------------
  
