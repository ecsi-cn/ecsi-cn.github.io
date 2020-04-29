---
layout: post
title:  "Typography"
date:   2020-04-28 14:22:41 +0800
categories: Typography
---

### Roboto
The primary font family to be used is **Roboto**. The font should degrade to **Sans-serif** in CSS if the user’s device does not support this custom web font. So far we are using 2 font weights out of the family: **Regular**, **SemiBold**.

<div class="panel panel-success">
    <div class="panel-heading">Example</div>
    <div class="panel-body">
        <p>Regular</p>
        <p style="font-size: 140px;">Aa</p>
        <p>
            ABCDEFGHIJKLMNOPQRSTUVWXYZ<br>
            abcdefghijklmnopqrstuvwxyz<br>
            (.,:;?!$@*) 0123456789
        </p>
    </div>
</div>

```html
<p>Aa</p>
<p>
    ABCDEFGHIJKLMNOPQRSTUVWXYZ<br>
    abcdefghijklmnopqrstuvwxyz<br>
    (.,:;?!$@*) 0123456789
</p>
```

<div class="panel panel-success">
    <div class="panel-heading">Example</div>
    <div class="panel-body">
        <p class="font-semibold">SemiBold</p>
        <p style="font-size: 140px;" class="font-semibold">Aa</p>
        <p class="font-semibold">
            ABCDEFGHIJKLMNOPQRSTUVWXYZ<br>
            abcdefghijklmnopqrstuvwxyz<br>
            (.,:;?!$@*) 0123456789
        </p>
    </div>
</div>

```html
<p class="font-semibold">Aa</p>
<p class="font-semibold">
    ABCDEFGHIJKLMNOPQRSTUVWXYZ<br>
    abcdefghijklmnopqrstuvwxyz<br>
    (.,:;?!$@*) 0123456789
</p>
```

### Headings
<div class="panel panel-success">
    <div class="panel-heading">Example</div>
    <div class="panel-body">
        <h1 class="h1">Main Title (Desktop and Tablet: 32px, Mobile: 24px)</h1>
        <h2 class="h2">Page title (Desktop and Tablet: 24px, Mobile: 20px)</h2>
        <h3 class="h3">Sub title (Desktop and Tablet: 18px, Mobile: 16px)</h3>
        <h4 class="h4">Normal title (Desktop and Tablet: 16px, Mobile: 14px)</h4>
    </div>
</div>

```html
<h1 class="h1">Main Title</h1>
<h2 class="h2">Page title</h2>
<h3 class="h3">Sub title</h3>
<h4 class="h4">Normal title</h4>
```

### Body text
Font size (Desktop and Tablet: 16px, Mobile: 14px)
<div class="panel panel-success">
    <div class="panel-heading">Example</div>
    <div class="panel-body">
        <p>Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nullam id dolor id nibh ultricies vehicula.</p>
        <p>Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec ullamcorper nulla non metus auctor fringilla. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Donec ullamcorper nulla non metus auctor fringilla.</p>
        <p>Maecenas sed diam eget risus varius blandit sit amet non magna. Donec id elit non mi porta gravida at eget metus. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.</p>
    </div>
</div>

```html
<p>
Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nullam id dolor id nibh ultricies vehicula.
</p>
<p>
Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec ullamcorper nulla non metus auctor fringilla. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Donec ullamcorper nulla non metus auctor fringilla.
</p>
<p>
Maecenas sed diam eget risus varius blandit sit amet non magna. Donec id elit non mi porta gravida at eget metus. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.
</p>
```

### Links
<div class="panel panel-success">
    <div class="panel-heading">Example</div>
    <div class="panel-body">
        <div>
            <a class="link" href="#">Text Link</a>
        </div>
        <div>
            <a class="link disabled" href="#">Disabled Text Link</a>
        </div>
    </div>
</div>

```html
<a class="link" href="#">Text Link</a>
<a class="link disabled" href="#">Disabled Text Link</a>
```