# websiteTest
## Git Commands
* `git status` tells whether something is commited or not 
* `git add` marks up for commitment 
* `git add .` marks up everything for commitment 
* `git commit -m "here is the message"` commits 
* `git push` pushes into remote repository 

## HTML
### Characters 
Some characters can't be used within the HTML syntax, instead there are other ways to write them:
* `>` becomes `&gt;`
* `<` becomes `&lt;`
* `&` becomes `&amp;`

Other characters are not easily found on keyboards 
* `©` becomes `&copy;`

Some characters change if there is a different charset that UTF-8 
* `"` can be written as `&quot;` to avoid weird characters

### Spacing 
To avoid two words from separating when the browser is bigger or smaller, use `&nbsp;` between the words instead of the space.

### Linking 
Inline Link:
```html
<a href='file-name.html' title="description">Here text displayed in website</a> 
```

New Line Link: 

```html
<a href="demofile.html" title="this is just a demo">
<div>Important stuff but in a new line </div>
</a>
```

Linking sections from the same page:
```html 
<a href="#section1">#section1</a>

<section id="section1">
    <h3>(#section1) Section 1</h3>
    <p>Lorem ipsum dolor sit amet, </p>
</section>
```