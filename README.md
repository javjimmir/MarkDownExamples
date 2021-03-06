
# MARKDOWN EXAMPLES 

#### Heading/Titles 

```
# Heading H1  #######
## Heading H2 #######
### Heading H3 ######
#### Heading H4 #####
##### Heading H5 ####
###### Heading H6 ###

Alt-H1
=======

Alt-H2
------
```

Translates to :

# Heading H1  #######
## Heading H2 #######
### Heading H3 ######
#### Heading H4 #####
##### Heading H5 ####
###### Heading H6 ###


Alt-H1
=======

Alt-H2
------

#### Text emphasis


``` Markdown
Bold: **Double Asterisks**   __Double Underlining__

Italic: *Single Asterisk*  _Single Underline_

Strikethrough: ~~Double tilde~~

Bold Italic : **Bold __Italic__**
```

Translates to 

Bold: **Double Asterisks**   __Double Underlining__

Italic: *Single Asterisk*  _Single Underline_

Strikethrough: ~~Double tilde~~

Bold Italic : **Bold _Italic_**


#### Lists

1. One
2. Two
3. Three
   * Three one
   * Three two
      1. Three two one
      2. Three two two
4. Four
    + Four one
    - Four two
    
#### HyperLinks

[Just an ordinary link](http://google.com)

[Just an orinary link but with a title](http://google.co.in "Google with an Indian twist")

[Just a link with supposed reference][AlrightHearMeOut]

[Just a link with supposed reference][AlrightHearMeOut]

[Just another link with number-style references][1]

[AlrightHearMeOut]: http://google.co.uk
[1]: http://reddit.com
[Does linking itself  work]: http://probablyyes.com

[Does linking itself work]

![Alt-text](https://www.google.co.in/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "Google logo image")

Reference style

![Alt-text][Google-Image]

[Google-Image]:https://www.google.co.in/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png

``` HTML
<HTML>
<HEAD>
<TITLE> Testing  Code syntax highlighting</TITLE>
</HEAD>
<BODY>
Good going, Google
</BODY>
</HTML>
```

    
``` python
print("Good going, Google")
breadfast = eggs + spam
print (type(breadfast)) #Remember you fork the ParserTongue everytime it gives an exception
```

#### Tables

| Col 1 | col 2 | col 3|
| --- | ---| ---|
Roses|are|red
|Violets|are|Blue|
|Gurl|you|though|
without|da|dashes

>> One line blockquote. Nothing much to write here.

>> "You know, they say, in my native mythology, there are seven diffferent persons in the world that are identical to each other. They may or may not meet each other in their lifetime. The thing is I tend to find the look alikes all the time and freak out if I am meddling with their alternate universes and ~~wish~~ secretly hope ~~to think~~ ~~what~~ change ~~I have brought to~~ their universe just by talking to them. If you are the real thing, I would be secretly *relieved* and if you are not, my day just becomes a *little* more infuriating."



