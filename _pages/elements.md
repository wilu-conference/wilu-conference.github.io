---
permalink: /elements/
layout: post
is_preload: true
title: "Elements<br />Reference"
---

<!-- Text stuff -->
## Text

This is __bold__ and this is <strong>strong</strong>. This is _italic_ and this is <em>emphasized</em>.
This is <sup>superscript</sup> text and this is <sub>subscript</sub> text.
This is <u>underlined</u> and this is code: <code>for (;;) { ... }</code>.
Finally, this is a [link</a>.

---

## Heading Level 2
### Heading Level 3
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6

---

<header markdown="1">
## Heading with a Subtitle
Lorem ipsum dolor sit amet nullam id egestas urna aliquam
</header>

Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor
sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet.
Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in
adipiscing blandit tempus accumsan.

<header markdown="1">
### Heading with a Subtitle
Lorem ipsum dolor sit amet nullam id egestas urna aliquam
</header>

Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor
sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet.
Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in
adipiscing blandit tempus accumsan.

<header markdown="1">
#### Heading with a Subtitle
Lorem ipsum dolor sit amet nullam id egestas urna aliquam
</header>

Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor
sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet.
Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in
adipiscing blandit tempus accumsan.

---

<!-- Lists -->
## Lists
<div class="row">
<div class="col-6 col-12-small" markdown="1">

### Unordered

 * Dolor pulvinar etiam.
 * Sagittis lorem eleifend.
 * Felis feugiat dolore viverra.
 * Dolor pulvinar etiam.

### Alternate

 * Dolor pulvinar etiam.
 * Sagittis lorem eleifend.
 * Felis feugiat dolore viverra.
 * Dolor pulvinar etiam.
{:.alt}

</div>
<div class="col-6 col-12-small" markdown="1">

### Ordered

 1. Dolor pulvinar etiam.
 2. Sagittis lorem eleifend.
 3. Felis feugiat dolore viverra.
 4. Dolor pulvinar etiam.
 5. Felis enim et tempus.

### Icons

 * [*Twitter*{:.label}](#){:.icon .fa-twitter}
 * [*Facebook*{:.label}](#){:.icon .fa-facebook}
 * [*Instagram*{:.label}](#){:.icon .fa-instagram}
 * [*Github*{:.label}](#){:.icon .fa-github}
 * [*Dribbble*{:.label}](#){:.icon .fa-dribbble}
{:.icons}

 * [*Twitter*{:.label}](#){:.icon .alt .fa-twitter}
 * [*Facebook*{:.label}](#){:.icon .alt .fa-facebook}
 * [*Instagram*{:.label}](#){:.icon .alt .fa-instagram}
 * [*Github*{:.label}](#){:.icon .alt .fa-github}
 * [*Dribbble*{:.label}](#){:.icon .alt .fa-dribbble}
{:.icons .alt}

</div>
</div>

### Definition

Item 1
: Lorem ipsum dolor vestibulum ante ipsum primis in faucibus vestibulum. Blandit
  adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus.
  Integer ac pellentesque praesent.

Item 2
: Lorem ipsum dolor vestibulum ante ipsum primis in faucibus vestibulum. Blandit
  adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus.
  Integer ac pellentesque praesent.

Item 3
: Lorem ipsum dolor vestibulum ante ipsum primis in faucibus vestibulum. Blandit
  adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus.
  Integer ac pellentesque praesent.

### Actions

  * [Primary](#){:.button .primary}
  * [Default](#){:.button}
{:.actions}

<ul class="actions small">
  <li><a href="#" class="button primary small">Small</a></li>
  <li><a href="#" class="button small">Small</a></li>
</ul>

<div class="row">
<div class="col-6 col-12-small" markdown="1">
  * [Primary](#){:.button .primary}
  * [Default](#){:.button}
{:.actions .stacked}
</div>
<div class="col-6 col-12-small" markdown="1">
  * [Small](#){:.button .primary .small}
  * [Small](#){:.button .small}
{:.actions .stacked}
</div>
</div>

<div class="row">
<div class="col-6 col-12-small" markdown="1">
  * [Primary](#){:.button .primary .fit}
  * [Default](#){:.button .fit}
{:.actions .stacked}
</div>
<div class="col-6 col-12-small" markdown="1">
  * [Small](#){:.button .primary .fit .small}
  * [Small](#){:.button .fit .small}
{:.actions .stacked}
</div>
</div>

---

<!-- Blockquote -->
## Blockquote

> Fringilla nisl. Donec accumsan interdum nisi, quis tincidunt felis sagittis
> eget tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum.
> Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan faucibus.
> Vestibulum ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu
> felis.

---

<!-- Table -->
## Table

### Default
<div class="table-wrapper" markdown="1">

| Name   | Description                             | Price  |
| :----- | :-------------------------------------- | :----- |
| Item 1 | Ante turpis integer aliquet porttitor.  | 29.99  |
| Item 2 | Vis ac commodo adipiscing arcu aliquet. | 19.99  |
| Item 3 | Morbi faucibus arcu accumsan lorem.     | 29.99  |
| Item 4 | Vitae integer tempus condimentum.       | 19.99  |
| Item 5 | Ante turpis integer aliquet porttitor.  | 29.99  |
|===========================================================|
|        |                                         | 100.00 |

</div>

### Alternate
<div class="table-wrapper" markdown="1">

| Name   | Description                             | Price  |
| :----- | :-------------------------------------- | :----- |
| Item 1 | Ante turpis integer aliquet porttitor.  | 29.99  |
| Item 2 | Vis ac commodo adipiscing arcu aliquet. | 19.99  |
| Item 3 | Morbi faucibus arcu accumsan lorem.     | 29.99  |
| Item 4 | Vitae integer tempus condimentum.       | 19.99  |
| Item 5 | Ante turpis integer aliquet porttitor.  | 29.99  |
|===========================================================|
|        |                                         | 100.00 |
{:.alt}

</div>

---

<!-- Buttons -->
## Buttons

  * [Primary](#){:.button .primary}
  * [Default](#){:.button}
{:.actions}

  * [Large](#){:.button .primary .large}
  * [Default](#){:.button}
  * [Small](#){:.button .small}
{:.actions}

  * [Fit](#){:.button .primary .fit}
  * [Fit](#){:.button .fit}
{:.actions .fit}

  * [Fit + Small](#){:.button .primary .fit .small}
  * [Fit + Small](#){:.button .fit .small}
{:.actions .fit .small}

  * [Icon](#){:.button .primary .icon .fa-search}
  * [Icon](#){:.button .icon .fa-download}
{:.actions}

  * [Primary](#){:.button .primary .disabled}
  * [Default](#){:.button .disabled}
{:.actions}

---

<!-- Form -->
## Form

<form method="post" action="#">
  <div class="row gtr-uniform">
    <div class="col-6 col-12-xsmall">
      <input type="text" name="demo-name" id="demo-name" value="" placeholder="Name" />
    </div>
    <div class="col-6 col-12-xsmall">
      <input type="email" name="demo-email" id="demo-email" value="" placeholder="Email" />
    </div>
    <!-- Break -->
    <div class="col-12">
      <select name="demo-category" id="demo-category">
        <option value="">- Category -</option>
        <option value="1">Manufacturing</option>
        <option value="1">Shipping</option>
        <option value="1">Administration</option>
        <option value="1">Human Resources</option>
      </select>
    </div>
    <!-- Break -->
    <div class="col-4 col-12-small">
      <input type="radio" id="demo-priority-low" name="demo-priority" checked>
      <label for="demo-priority-low">Low</label>
    </div>
    <div class="col-4 col-12-small">
      <input type="radio" id="demo-priority-normal" name="demo-priority">
      <label for="demo-priority-normal">Normal</label>
    </div>
    <div class="col-4 col-12-small">
      <input type="radio" id="demo-priority-high" name="demo-priority">
      <label for="demo-priority-high">High</label>
    </div>
    <!-- Break -->
    <div class="col-6 col-12-small">
      <input type="checkbox" id="demo-copy" name="demo-copy">
      <label for="demo-copy">Email me a copy</label>
    </div>
    <div class="col-6 col-12-small">
      <input type="checkbox" id="demo-human" name="demo-human" checked>
      <label for="demo-human">I am a human</label>
    </div>
    <!-- Break -->
    <div class="col-12">
      <textarea name="demo-message" id="demo-message" placeholder="Enter your message" rows="6"></textarea>
    </div>
    <!-- Break -->
    <div class="col-12">
      <ul class="actions">
        <li><input type="submit" value="Send Message" class="primary" /></li>
        <li><input type="reset" value="Reset" /></li>
      </ul>
    </div>
  </div>
</form>

---

<!-- Image -->
## Image

### Fit
*![]({{ 'assets/images/pic01.jpg' | relative_url }})*{:.image .fit}

<div class="box alt">
  <div class="row gtr-50 gtr-uniform">
    <div class="col-4"><span class="image fit"><img src="{{ 'assets/images/pic02.jpg' | relative_url }}" alt="" /></span></div>
    <div class="col-4"><span class="image fit"><img src="{{ 'assets/images/pic03.jpg' | relative_url }}" alt="" /></span></div>
    <div class="col-4"><span class="image fit"><img src="{{ 'assets/images/pic04.jpg' | relative_url }}" alt="" /></span></div>
    <!-- Break -->
    <div class="col-4"><span class="image fit"><img src="{{ 'assets/images/pic04.jpg' | relative_url }}" alt="" /></span></div>
    <div class="col-4"><span class="image fit"><img src="{{ 'assets/images/pic02.jpg' | relative_url }}" alt="" /></span></div>
    <div class="col-4"><span class="image fit"><img src="{{ 'assets/images/pic03.jpg' | relative_url }}" alt="" /></span></div>
    <!-- Break -->
    <div class="col-4"><span class="image fit"><img src="{{ 'assets/images/pic03.jpg' | relative_url }}" alt="" /></span></div>
    <div class="col-4"><span class="image fit"><img src="{{ 'assets/images/pic04.jpg' | relative_url }}" alt="" /></span></div>
    <div class="col-4"><span class="image fit"><img src="{{ 'assets/images/pic02.jpg' | relative_url }}" alt="" /></span></div>
  </div>
</div>

### Left &amp; Right

*![]({{ 'assets/images/pic08.jpg' | relative_url }})*{:.image .left}
Lorem ipsum dolor sit accumsan interdum nisi, quis tincidunt felis sagittis
eget. tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum.
Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus.
Integer ac pellentesque praesent tincidunt felis sagittis eget. tempus euismod.
Vestibulum ante ipsum primis sagittis eget. tempus euismod. Vestibulum ante
ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis
volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent
tincidunt felis sagittis eget. tempus euismod. Vestibulum ante ipsum primis in
faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing
accumsan eu faucibus. Integer ac pellentesque praesent. Vestibulum ante ipsum
primis in faucibus magna blandit adipiscing eu felis iaculis.

*![]({{ 'assets/images/pic08.jpg' | relative_url }})*{:.image .right}
Lorem ipsum dolor sit accumsan interdum nisi, quis tincidunt felis sagittis
eget. tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum.
Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus.
Integer ac pellentesque praesent tincidunt felis sagittis eget.  tempus euismod.
Vestibulum ante ipsum primis sagittis eget. tempus euismod.  Vestibulum ante
ipsum primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis
volutpat ac adipiscing accumsan eu faucibus. Integer ac pellentesque praesent
tincidunt felis sagittis eget. tempus euismod. Vestibulum ante ipsum primis in
faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing
accumsan eu faucibus. Integer ac pellentesque praesent. Vestibulum ante ipsum
primis in faucibus magna blandit adipiscing eu felis iaculis.

---

<!-- Box -->
## Box

Felis sagittis eget tempus primis in faucibus vestibulum. Blandit adipiscing eu
felis iaculis volutpat ac adipiscing accumsan eu faucibus. Integer ac
pellentesque praesent tincidunt felis sagittis eget. tempus euismod. Magna sed
etiam ante ipsum primis in faucibus vestibulum. Blandit adipiscing eu ipsum
primis in faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac
adipiscing accumsan eu faucibus lorem ipsum dolor sit amet nullam. Integer ac
pellentesque praesent tincidunt felis sagittis eget. tempus euismod. Vestibulum
ante ipsum primis sagittis eget. tempus euismod. Vestibulum ante ipsum primis in
faucibus vestibulum. Blandit adipiscing eu felis iaculis volutpat ac adipiscing
accumsan eu faucibus. Integer ac pellentesque praesent tincidunt felis sagittis
eget. tempus euismod. Vestibulum ante ipsum primis in faucibus vestibulum.
Blandit adipiscing eu felis iaculis volutpat ac adipiscing accumsan eu faucibus.
Integer ac pellentesque praesent. Vestibulum ante ipsum primis in faucibus magna
blandit adipiscing eu felis iaculis volutpat lorem ipsum dolor.
{:.box}


---

<!-- Preformatted Code -->
## Preformatted

```
i = 0;

while (!deck.isInOrder()) {
    print 'Iteration ' + i;
    deck.shuffle();
    i++;
}

print 'It took ' + i + ' iterations to sort the deck.';
```
