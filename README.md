
# <font color=pink>Markdown Tutorial</font>

Markdown is a file type that allows us to easily and quickly format text documents. It is really common on internet and we find it in almost every repositories, specially as a **README** file.

Here we present some syntaxis used in md files so you can easily start styling your text files:

<a id="summary"></a>

1. [Headings](#headings)
2. [Font styles](#font-styles)
	* [Italic](#italic)
	* [Bold](#bold)
	* [Bold and Italic](#bold-and-italic)
	* [Strikethrough](#strikethrough)
3. [Document formats](#document-formats)
	* [Lists](#lists)
	* [Task Lists](#tasks-lists)
	* [Tables](#tables)
	* [Horizontal Bar](#horizontal-bar)
4. [Codes and Quotes](#codes-and-quotes)
	* [Code](#code)
	* [Code Block](#code-block)
	* [Quote and Blockquote](#quote-and-blockquote)
5. [Images](#images)
6. [Links](#links)
	* [Anchor links](#anchor-links)
7. [HTML tags](#html-tags)
	* [Color](#color)
	* [Size](#size)
	* [Mixed styles](#mixed-styles)
* [Document information](#document-information)

<br>

## <a id="headings"></a><font color="yellow">1. Headings</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
---

<br>

Headings are used to create titles. The font size is bigger and more strong, and it adds blank space on top and bottom of the title. The main important Heading, equivalent to an H1 in HTML, is formated by used a #. Subtitles are created addind ##s.
Normally you will have only one # title (H1) on your document, that's the main title. And all the other topics should be subtitles (from ## to ######);

Below, you can see what you have to type and the results you get. Note that the space after the # is mandatory, or title won't be generated:

<font size=1 color=pink>Typed text: </font>  
`# My main title`

<font size=1 color=pink>Results: </font>

># My main title

---
<font size=1 color=pink>Typed text: </font>  
`## My subtitle`

<font size=1 color=pink>Results: </font>

>## My subtitle

---
<font size=1 color=pink>Typed text: </font>  
`### My subtitle  (3rd level)`

<font size=1 color=pink>Results: </font>

>### My subtitle (3rd level)

---
<font size=1 color=pink>Typed text: </font>  
`#### My subtitle (4th level)`

<font size=1 color=pink>Results: </font>

>#### My subtitle (4th level)

---
<font size=1 color=pink>Typed text: </font>  
`##### My small subtitle (5th level)`

<font size=1 color=pink>Results: </font>

>##### My small subtitle (5th level)

---
<font size=1 color=pink>Typed text: </font>  
`###### My very small subtitle (6th level)`

<font size=1 color=pink>Results: </font>

>###### My very small subtitle (6th level)

_**note**: as a special case, you could also create a main title (# - H1) or a subtitle (## - H2) using === or --- below the text. But normally you would do it using with # or ## as seen above, it is easier and more common. See the examples:_

<font size=1 color=pink>Typed text: </font>  
`My main title`
`===`

<font size=1 color=pink>Results: </font>

>My main title
>===

<font size=1 color=pink>Typed text: </font>  
`My subtitle`
`---`

<font size=1 color=pink>Results: </font>

>My subtitle
>---



<br><br>

## <a id="font-styles"></a><font color="yellow">2. Font styles</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
---

<br>

### - <a id="italic"></a><font color="lightblue">Italic</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>

Italic is used to highlight a word or sentence. Normally used for words in foreign languages, technical concepts, etc.
You can use italic with an underline \_ before and another after the word or sentence. There should be no space between the \_ and the word.

<font size=1 color=pink>Typed text: </font>  
`The Spanish word _ordenador_ is in italic`

<font size=1 color=pink>Results: </font>
>The Spanish word _ordenador_ is in italic

<br>

<font size=1 color=pink>Typed text: </font>  
`_This is a full sentence in italic_`

<font size=1 color=pink>Results: </font>
>_This is a full sentence in italic_

<br>

The same results can be achieved using asteristic *:
<font size=1 color=pink>Typed text: </font>  
`_Asteristic_ have the same effect as _underline_.`

<font size=1 color=pink>Results: </font>
>_Asteristic_ have the same effect as _underline_.

<br>

### - <a id="bold"></a><font color="lightblue">Bold</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>

Bold is used to give particular emphasys to a word or sentence.
You can use bold with **two** underlines __ before and another **two** after the word or sentence. Like with italic, there should be no space between the __ and the word.
You can also use **two** asteristics **.

<font size=1 color=pink>Typed text: </font>  
`Front end Developer is a __great__ job.`

<font size=1 color=pink>Results: </font>
>Front end Developer is a __great__ job.

<br>

<font size=1 color=pink>Typed text: </font>  
`The word **help** has emphasys.`

<font size=1 color=pink>Results: </font>
>The word **help** has emphasys.

<br>

<font size=1 color=pink>Typed text: </font>  
`__This is a full bold sentence__`

<font size=1 color=pink>Results: </font>
>__This is a full bold sentence__

<br>

### - <a id="bold-and-italic"></a><font color="lightblue">Bold and Italic</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>

You can use both italic and bold at the same time.

<font size=1 color=pink>Typed text: </font>  
`_Italic_ word and __Bold__ word`

<font size=1 color=pink>Results: </font>
>_Italic_ word and __Bold__ word

<br>

<font size=1 color=pink>Typed text: </font>  
`The word ___Love___ has both italic and bold styles.` or
`The word ***Love*** has both italic and bold styles.`

<font size=1 color=pink>Results: </font>
>The word ___Love___ has both italic and bold styles.

<br>

<font size=1 color=pink>Typed text: </font>  
` ___This is a full bold and italic sentence___` or
` ***This is a full bold and italic sentence***` or

<font size=1 color=pink>Results: </font>
>***This is a full bold and italic sentence***

<br>

### - <a id="strikethrough"></a><font color="lightblue">Strikethrough</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>

It is used to highlight that some word or sentence has been erased or should not be used. You use double tilde ~~

<font size=1 color=pink>Typed text: </font>  
`You mistyped the command. Please change ~~fech~~ to *fetch*.`

<font size=1 color=pink>Results: </font>
>You mistyped the command. Please change ~~fech~~ to *fetch*.


<br>

## <a id="document-formats"></a><font color="yellow">3. Document formats</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
---

<br>

### - <a id="lists"></a><font color="lightblue">Lists</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
Lists are created to organize topics. You can have a numbered list, using numbers, or a bullet list, using -, + or *.

<font size=1 color=pink>Typed text: </font>  
` My list:`  
`1. Item one`  
`2. Item two`  
`3. Item three`  

<font size=1 color=pink>Results: </font>
>My list:
>1. Item one
>2. Item two
>3. Item three

<br>

<font size=1 color=pink>Typed text: </font>  
` My bullet list:`  
`- One item`  
`- Another item`  
`- One more item`  

<font size=1 color=pink>Results: </font>
> My bullet list:
>- One item
>- Another item
>- One more item

<br>

_The symbols + and * create an empty space between items. They both work exactly the same way and could be exchanged one for another_.

<font size=1 color=pink>Typed text: </font>  
` My bullet list:`  
`* One item`  
`+ Another item`  
`+ One more item`  

<font size=1 color=pink>Results: </font>
> My bullet list:
>* One item
>- Another item
>+ One more item

<br>

### - <a id="tasks-lists"></a><font color="lightblue">Task Lists</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
Tasks list as used to take note of tasks and if they are completed or not. You use the same notation as lists (-, + or *) followed by brackets [  ].
You can add an ***x*** to mark task as completed.

<font size=1 color=pink>Typed text: </font>  
`My to-do list:`  
`- [x] Wake up`  
`- [ ] Have some coffee`  
`- [ ] Study`  

<font size=1 color=pink>Results: </font>
>My to-do list:
>- [x] Wake up
>- [ ] Have some coffee
>- [ ] Study

<br>

### - <a id="tables"></a><font color="lightblue">Tables</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
Tables are used to organize information. The table cells are separated by |
and you need to separate the table header from the body using a --- separator
It is alno needed to leave an empty line before the table, or it won't render correctly on some viewers, like on Github.

<font size=1 color=pink>Typed text: </font>  
`My table`  
``
`| Day | Class |`  
`|---|---|`  
`| Monday | yes |`  
`| Tuesday | no |`  
`| Wednesday | yes |`  
`| Thursday | no |`  
`| Friday | no |`  

<font size=1 color=pink>Results: </font>
>My table

>| Day | Class |
>|---|---|
>| Monday | yes |
>| Tuesday | no |
>| Wednesday | yes |
>| Thursday | no |
>| Friday | no |


<br>

### - <a id="horizontal-bar"></a><font color="lightblue">Horizontal Bar</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
This is a bar that separates sections on your text document. You use a --- on a blank line.

<font size=1 color=pink>Typed text: </font>  
`One section`  
` `  
`---`  
`Another section`  

<font size=1 color=pink>Results: </font>
>One section
>
>---
>Another section

**note**: because of the special case ___ for generating titles, you should put a blank like after the text

<font size=1 color=pink>Typed text:</font>  
`One section`  
`---`  
`Another section`  

<font size=2 color=red>_Doesn't work as expected. It converts the upper text to a title:_</font>
<font size=1 color=pink>Results: </font>
>One section
>---
>Another section


<br>

## <a id="codes-and-quotes"></a><font color="yellow">4. Codes and Quotes</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
---

<br>

### - <a id="code"></a><font color="lightblue">Code</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
Code is used when we want to highlight a line, stating that it is a piece of code. This is important to catch the attention and state that the code is not a normal text. You use a backtick ` before and after the code.
It is used every time by programmers to display to others pieces of code.

<font size=1 color=pink>Typed text: </font>  
`` `<p>This is a piece of code.</p>` ``  

<font size=1 color=pink>Results: </font>
>`<p>This is a piece of code.</p>`

Note that other Markdown or HTML tags won't work inside a code sentence. That's the main advantage of using a code. We can display the tags without aplying the styles. It is very useful for teaching . 😉

<font size=1 color=pink>Typed text: </font>  
`` `The Spanish word _ordenador_ is in italic` ``

<font size=1 color=pink>Results: </font>
>`The Spanish word _ordenador_ is in italic`

_Note the difference without the backticks `_ :

<font size=1 color=pink>Typed text: </font>  
`The Spanish word _ordenador_ is in italic`

<font size=1 color=pink>Results: </font>
>The Spanish word _ordenador_ is in italic

<br>

note: it only works for a single line code. If you want to display more than one line of code, you need to use a Code block (see below).

<font size=1 color=pink>Typed text: </font>  
`` `<!doctype html>``  
`<html lang="en">`  
`<head>`  
`<title>My Page</title>`  
`</head>`  
`<body>`  
`<h1>My Page</h1>`  
`</body>`  
`</html>`  
`` ` ``

<font size=2 color=red>_It doesn't work as expected._</font>
<font size=1 color=pink>Results: </font>
>`<!doctype html>
>	<html lang="en">
>	<head>
>		<title>My Page</title>
>	</head>
>	<body>
>		<h1>My Page</h1>
>	</body>
></html>
>`

<br><br>

### - <a id="code-block"></a><font color="lightblue">Code Block</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
Code Block is used exactly as the Code, but when we want to display a multiline code. We start a Code Block with triple backtick \``` and finish it the same way \```.

<font size=1 color=pink>Typed text: </font>  

`` ``` ``  
`<!doctype html>`  
`<html lang="en">`  
`  <head>`  
`    <title>My Page</title>`  
`  </head>`  
`  <body>`  
`    <h1>My Page</h1>`  
`  </body>`  
`</html>`  
`` ``` ``  


<font size=1 color=pink>Results: </font>
>```
><!doctype html>
><html lang="en">
><head>
><title>My Page</title>
></head>
><body>
><h1>My Page</h1>
></body>
></html>
>```

<br>

**note**: _inside Code Blocks, you can add_ spaces _and_ tabs _to give your code a correct indentation, so it is clearer to be read and understood._
<font size=1 color=pink>Typed text: </font>  

`` ``` ``  
`<!doctype html>`  
`<html lang="en">`  
` `&nbsp;&nbsp;&nbsp;&nbsp;`<head>`  
` `&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`<title>My Page</title>`  
` `&nbsp;&nbsp;&nbsp;&nbsp;` </head>`  
` `&nbsp;&nbsp;&nbsp;&nbsp;` <body>`  
` `&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`   <h1>My Page</h1>`  
` `&nbsp;&nbsp;&nbsp;&nbsp;` </body>`  
`</html>`  
`` ``` ``  


<font size=1 color=pink>Results: </font>
>```
><!doctype html>
><html lang="en">
>  <head>
>    <title>My Page</title>
>  </head>
>  <body>
>    <h1>My Page</h1>
>  </body>
></html>
>```

<br>

**note**: _Just like with single line Codes, Mardkdown and HTML tags are not converted to styles_
<font size=1 color=pink>Typed text: </font>  

`` ``` ``  
`This is a **bold** text.`  
`This is an _italic_ text.`  
`This is a ~~strikethrough~~ text`  
`` ``` ``  


<font size=1 color=pink>Results: </font>
>```
>This is a **bold** text.
>This is an _italic_ text.
>This is a ~~strikethrough~~ text
>```

**note**: _you can also use the Code Block triple backtick ``` for single line Code, and it will work exactly like the single backtick ` Code's syntaxis._
<font size=1 color=pink>Typed text: </font>  

`` ``` <p>Hello World!</p> ``` ``  


<font size=1 color=pink>Results: </font>
>```Hello World!```

<br>

### - <a id="quote-and-blockquote"></a><font color="lightblue">Quote and Blockquote</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
Quote is a format we use when we want to hightlight a sentence stating that it is a quote. It creates a distinct block around the sentence.
It is created using a _greaten than_ > character before the sentence.
In practical terms, it works like Code Block, but Markdown and HTML tags are applied and give styles to text.

<font size=1 color=pink>Typed text: </font>  

`>This is a _quote_.`  


<font size=1 color=pink>Results: </font>
>This is a _quote_.


<br>

**note**: _Quote blocks works exactly the same way, but with multiple lines. We need to put a > before each line ane they get grouped together._
<font size=1>Typed text: </font>  

`>_I always did something I was a little not ready to do. I think that’s how you grow. When there’s that moment of_ "Wow, I’m not really sure I can do this!" _and you push through those moments, that’s when you have a breakthrough._`  
`>`  
`>— Marissa Mayer (CEO of Yahoo)`  

<font size=1 color=pink>Results: </font>
>_I always did something I was a little not ready to do. I think that’s how you grow. When there’s that moment of_ "Wow, I’m not really sure I can do this!" _and you push through those moments, that’s when you have a breakthrough._
>
>— Marissa Mayer (CEO of Yahoo)

<br>

## <a id="images"></a><font color="yellow">5. Images</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
---

<br>

You can add images to your Mardown documents. You just need to know the exact path of the image and provide an alt text.
_Alt texts_ are texts describing your image. It is very helpful for people with special necessities (such as blind people) using screen readers. As they can't see the image, the _Alt text_ describes the image for them. We should **always** provide an _Alt text_ for images.
Normally, the Alt text is not displayed on screen.

Sintaxis: `![Alt text](path to the photo)`
<font color=crimson>_Pay attention on the exclamation ! before the brackets. It is necessary to load images._</font>

<font size=1 color=pink>Typed text: </font>  
`![Dove flying holding an olive branch symbolizing peace on earth](peace.png)`  

<font size=1 color=pink>Results: </font>
><a id="peace"></a>![Dove flying holding an olive branch symbolizing peace on earth](peace.png)

<br>
 **note**: _if your image is not on the same folder as your Mardkdown document, you need to inform the correct folder where the image can be found. In the example below we are acccesing an image that is inside an "images" folder._

<font size=1 color=pink>Typed text: </font>  
`![Logotype of Madrid For Refugees](images/madridforrefugees-logo.png)`  

<font size=1 color=pink>Results: </font>
>![Logotype of Madrid For Refugees](images/madridforrefugees-logo.png)

<br>

The most common extensions of images on the web are: .jpg .png .gif and .svg. Make sure you write the correctly the file extension as it is really common to mistake it.

**note**: _if your write a wrong extension or a wrong path, or if for any other reason the image can't be loaded, only the Alt text will be displayed. In the example below we've written a wrong file extension:_

<font size=1 color=pink>Typed text: </font>  
`![Logotype of Madrid For Refugees](images/madridforrefugees-logo.jpg)`  

<font size=1 color=pink>Results: </font>
>![Logotype of Madrid For Refugees](images/madridforrefugees-logo.jpg)

<br>

**note**: _If we do not inform correctly the folder that contains our image, it will not be able to be loaded, thus only the_ Alt text _will be displayed._
_Below, we removed the reference to the subfolder "images/" from the path and the Markdown will try to find the image on the same folder of the Markdown document._

<font size=1 color=pink>Typed text: </font>  
`![Logotype of Madrid For Refugees](madridforrefugees-logo.png)`  

<font size=1 color=pink>Results: </font>
>![Logotype of Madrid For Refugees](madridforrefugees-logo.png)

<br>

We can provide an internet address (URL) for an image. The advantage is that we don't have to host the image on our own project, but we have to take care not to use images protected by copyrights.

<font size=1 color=pink>Typed text: </font>  
`![Animated image of an Unicorn running and jumping](https://vignette.wikia.nocookie.net/animal-jam-clans-1/images/3/30/Unicorn.gif)`  

<font size=1 color=pink>Results: </font>
><a id="unicorn"></a>![Animated image of an Unicorn running and jumping](https://vignette.wikia.nocookie.net/animal-jam-clans-1/images/3/30/Unicorn.gif)


<br>

## <a id="links"></a><font color="yellow">6. Links</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
---

<br>

Just like on an HTML page, you can add hyperlinks to your Mardown document. Hyperlinks, or just links, are clickable partes od the document that take you to another document or page.
The sintaxis is almost the same as the Image's, but here we don't use the exclamation ! mark.

Sintaxis: `[Title](path or URL of link)`

**Title** is the text displayed informing where the link leads to. It is very important for understanding the purpose of the link, as normally the path or URL is not visible.

<font size=1 color=pink>Typed text: </font>  
`[Visit my Github page](https://github.com/annabranco)`  

<font size=1 color=pink>Results: </font>
>[Visit my Github page](https://github.com/annabranco)

_Clicking on this link is going to take you to my Github page. if you try it, remember to come back here to keep on learning._ 😉

Another useful function of links is to lead the reader to an specific part or section of your document.

For example, you want users to go to Section One Heading when they click on "Section One" summary item.

Summary:
1. <font color=skyblue>Section One</font> `(clicking here...)`
2. Section Two

## <font color=skyblue>Section One </font><font size=2>`(...would take users to this section)`</font>

To do it, we just need to create a link to the name of the Heading, using only lowercase letters and changing spaces for dashes - .

In this case, our link would be `[Section One](#section-one)`

Let's write our code:

<font size=1 color=pink>Typed text: </font>  
`Summary:`  
`1. [Section One](#section-1)`  
`2. Section Two`  

<font size=1 color=pink>Results: </font>
>Summary:
>1. [Section One](#section-one)
>2. Section Two

<br>

Now clicking on Section One link on the above summary would take you directly to the Heading Section One below. Try it! 🙂

## Section One

Great, isn't it?

<br>

### - <a id="anchor-links"></a><font color="lightblue">Anchor links</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
Another way to establish links, when we are not able to use the Heading method described above, is to create an Anchor.
To do so, we create an **a** tag with the ID name we want to call our link reference.

For example, we want a link "TAKE ME TO MADRID FOR REFUGEES LOGO" to take us to the logotype displayed below:

<a id="our-logo"></a>![Logotype of Madrid For Refugees](images/madridforrefugees-logo.png)

The first step would be to put the **a** tag before the image sintaxis. Inside the `<a>` we need to give an ID, that would be how we want to call this Anchor. In our case, let's say "our-logo". So this would be the Anchor tag: `<a id="our-logo"></a>`

By placing it before our image, the code would be like this:

`<a id="our-logo"></a>![Logotype of Madrid For Refugees](images/madridforrefugees-logo.png)`

Using this sintaxis you can give names and create links for any part of your document.

Now, to create the link itself, we just need to add a path to the name we gave our Anchor.

This would be our code:
<font size=1 color=pink>Typed text: </font>
`[TAKE ME TO MADRID FOR REFUGEES LOGO](#our-logo)`

<font size=1 color=pink>Results: </font>
>[TAKE ME TO MADRID FOR REFUGEES LOGO](#our-logo)

Now, clicking on the above link will take you to the Logo of Madrid For Refugees. Pretty cool!

The summary on the beginning of this Tutorial uses this exact functionality.

<br>

## <a id="html-tags"></a><font color="yellow">7. HTML tags</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
---

<br>

Many developers don't like using HTML inside Markdown documents, and it is important to know that it is not fully supported. There are lot of viewers that just don't render HTML styles.
One another strong argument against it is that Markdown is another language, used to simplify and make it easier and quicker to write text documents. Thus, putting HTML code on it contradicts the logic of working with Markdown.

Some people like to use HTML tags just to give Markdown special styles that this language doesn't support by itself, like changing colors, font sizes, etc. But it is important to know that in many places, like here on Github, the effects will just not be seen.

If you decide to use it, here are some useful HTML tags:

<br>

### - <a id="color"></a><font color="lightblue">Color</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>

To change the color of the text, we can use the HTML tag `<font>` with the attribute `color`. We just need to write the name or code of the color. A pink color, for example, would be `<font color=pink>`.
We wrap the text we want to change colors on the `<font></font>` tag.

<font size=1 color=pink>Typed text: </font>  
`The word <font color=red>red</font> is red and <font color=green>green</font> is green.`  

<font size=1 color=pink>Results: </font>
>The word <font color=red>red</font> is red and <font color=green>green</font> is green.

If you want to know more about color codes and names, here is a good page: Color codes and names on HTML/CSS.

<br>

### - <a id="size"></a><font color="lightblue">Size</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>

To change the color of the text, we can also use the HTML tag `<font>`, with the attribute `size`

<font size=1 color=pink>Typed text: </font>  
`<font size=6>Huge text</font>`  
`<font size=5>Very big text</font>`  
`<font size=4>Big text</font>`  
`<font size=3>Normal text</font>`  
`<font size=3>Almost normal text</font>`  
`<font size=2>Small text</font>`  
`<font size=1>Very small text</font>`  
`<font size=0>Tiny text</font>`  

<font size=1 color=pink>Results: </font>  
><font size=6>Huge text</font>  
<font size=5>Very big text</font>  
<font size=4>Big text</font>  
<font size=3>Normal text</font>  
<font size=3>Almost normal text</font>  
<font size=2>Small text</font>  
<font size=1>Very small text</font>  
<font size=0>Tiny text</font>  

<br>

### - <a id="mixed-styles"></a><font color="lightblue">Mixed styles</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>

Both mentioned styles can be grouped inside `<font>` tag.

<font size=1 color=pink>Typed text: </font>  
`The word <font color=red size=4>red</font> is red and <font color=lightgreen size=1>green</font> is green.`  

<font size=1 color=pink>Results: </font>
>The word <font color=red size=4>red</font> is red and <font color=lightgreen size=1>green</font> is green.

You can even mix up HTML and Markdown sintaxis.

<font size=1 color=pink>Typed text: </font>  
`The word <font color=red size=5>**red**</font> is red and bold <font color=lightgreen size=6>_green_</font> is green and italic.`  

<font size=1 color=pink>Results: </font>
>The word <font color=red size=5>**red**</font> is red and bold <font color=lightgreen size=6>_green_</font> is green and italic.

<br>

It is worth mentioning that even though these sintaxis are part of HTML, it should not be used inside HTML bodies, as the correct practice when writing HTML5 is that it holds just plain containt, and all styles are given through CSS3, that uses almost the same sintaxis.

<br>

### <a id="document-information"></a><font color="yellow">Document information</font>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <font size=1>[<< Back to Summary >>](#summary)</font>
---
Author: [Anna Branco](https://github.com/annabranco)
Version: 1.1
Updated on: Dicember 1st, 2018
Web page: [Markdown Tutorial](https://github.com/annabranco/markdown-tutorial)

Credits for the images:

- **[Dove flying holding an olive branch symbolizing peace on earth](#peace)**. Copyright: no. From [Wikipedia](https://en.wikipedia.org/wiki/File:Dove_peace.svg). _Licensed under the **Creative Commons Attribution-Share Alike 3.0 Unported license**_

- **[Logotype of Madrid For Refugees](#our-logo)**. _Version improved on Photoshop._ Copyrights: Madrid For Refugees.

- **[Animated image of an Unicorn running and jumping](#unicorn)**. Copyrights: [Wikia](https://github.com/Wikia/vignette). _Distributed under the **Eclipse Public License**._

<br>

This document may be freely distributed and I'd be really happy if it is used for educational purposes.

Please feel free to make any corrections, sugerencies or comments through _Pull Requests_.

I hope this is useful. Thank you. 😄
