##Geekwise Introduction to `<HTML>` and `CSS`
###Friday
###Date: 09-04-2015

##Overview
### 1: Review important concepts from the prior day

## HTML Hierarchy

### Creating the full `HTML` markup for the Browser to read the document.

```
<html>
  <head>
    <style>
    	body{
    			background-color:lightGrey;
    	};
    </style>
  </head>
 <body>   
    <ol>
			<li>HTML<li>
			<li>CSS<li>
			<li>STYLE<li>
		</ol>    
 </body>
</html>
```

## The `DIV` tag and using the `CSS` property `:hover`

```
    <style>
    	div{
    			background-color:grey;
    	};
			div:hover{
			    background-color:lightGrey;
    	}
    </style>
```


### 2: Share an overview of what will they will learn today
* Creating a simple team table webpage
* Using all of the `10` tags from the week
* Linking the pages together and uploading to the internet for a live CodeOff (presentation + demo)
* Working and presenting as a team your one page team site.

### 3: Practice exercise related to concept and objective
* Morning exercise in <http://www.codepen.io> writing a full `HTML` document using the 10 `<tags>` you will include into team site.
* Apply `CSS` with the `STYLE` tag and the `tag:hover` attribute for `CSS`
 
### 4: Closing session and circling back to objective of the day
* Software is built in teams
* Together we can build larger applications and internet sites
* We now can create a simple site that links to other pages on the internet and within the same site.

---
#1: Navigation And Naming Files for the Internet

### index.html is the main file for the browser to look at on a webpage.

### when linking to other pages the `href` will be the name of the file.

Use names that have dashes `-` for example

```
my-file-name.html
```
* not spaces. only dashes `-` with a file name of `.html`


## What was taught the day prior?
* Using the `DIV` tag as a container.
* Using the `:hover` attribute inside `CSS`
* Creating simple interactivity with state changes between attributes inside `CSS`


> ```
> <style type='text/css'>
> div{
> 	background-image:url(link-to-image.jpg);
> } 
> div:hover{
> 	background-image:url(link-to-another-image.jpg);
> } 
> </style>
> ```


#Types of Selectors

 * 1: element
 * 2: id
 * 3: class
 * 4: position in document 


#Types of Selectors: element
```
p{
	color: yellow;
}
```

> Selects all `P` elements in the entire document.


#Types of States For Selectors: hover

```
p:hover{
	background-color:lightYellow;
}
```