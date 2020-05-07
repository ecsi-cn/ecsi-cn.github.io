---
layout: post
title:  "Typography"
date:   2020-04-28 14:22:41 +0800
categories: Typography
---

### Roboto
The primary font family to be used is **Roboto**. The font should degrade to **Sans-serif** in CSS if the user’s device does not support this custom web font. 

So far we are using 2 font weights out of the family: **Regular**, **SemiBold**.

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

### Body text
Font size (Desktop and Tablet: 16px, Mobile: 14px)
<div class="panel panel-success">
    <div class="panel-heading">Example</div>
    <div class="panel-body">
        <p style="margin: 0">Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nullam id dolor id nibh ultricies vehicula.</p>
        <p style="margin: 0">Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec ullamcorper nulla non metus auctor fringilla. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Donec ullamcorper nulla non metus auctor fringilla.</p>
        <p style="margin: 0">Maecenas sed diam eget risus varius blandit sit amet non magna. Donec id elit non mi porta gravida at eget metus. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.</p>
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
            <a class="blue-link" href="#">Blue Link</a>
        </div>
        <div style="background-color: #00467E;">
            <a class="white-link" href="#">White Link when background is dark</a>
        </div>
    </div>
</div>

```html
<a class="blue-link" href="#">Blue Link</a>
<a class="white-link" href="#">White Link when background is dark</a>
```

### Disabled state
<div class="panel panel-success">
    <div class="panel-heading">Example</div>
    <div class="panel-body">
        <div>
            <a class="blue-link disabled" href="#">Disabled Blue Link</a>
        </div>
        <div style="background-color: #00467E;">
            <a class="white-link disabled" href="#">Disabled White Link</a>
        </div>
    </div>
</div>

```html
<a class="blue-link disabled" href="#">Disabled Blue Link</a>
<a class="white-link disabled" href="#">Disabled White Link</a>
```