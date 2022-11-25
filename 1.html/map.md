# Map

## Example

```html
    <!DOCTYPE html>
    <html>
    <head>
    <title>文档标题</title>
    </head>
    <body>
    可见文本...
    </body>
    </html>

```

## Basic tags
```html
    <h1>Big text</h1>
    <h2> . . . </h2>
    <h3> . . . </h3>
    <h4> . . . </h4>
    <h5> . . . </h5>
    <h6>Small text</h6>
    
    <p>Section</p>
    <br> （Line feed）
    <hr> Horizontal line
    <!-- 这是注释 -->
    Formatting
    <b>Bold</b>
    <code>Computer code</code>
    <em>Stress text</em>
    <i>Italic</i>
    <kbd>Keybord</kbd> 
    <pre>Format text</pre>
    <small>Small text</small>
    <strong>Important text</strong>
    
    <abbr> （Abridge）
    <address> （Concat message）
    <bdo> （Text direction）
    <blockquote> （Other origin）
    <cite> （Job's name）
    <del> （Remove text）
    <ins> （Inset text）
    <sub> （Down text）
    <sup> （On text）
```
## Links
```html
Base link：<a href="http://www.example.com/">Link text</a>
Image link： <a href="http://www.example.com/"><img decoding="async" src="URL" alt="replace text"></a>
Email link： <a href="mailto:webmaster@example.com">post e-mail</a>
Book index：
<a id="tips">prompt</a>
<a href="#tips">break</a>
```
### Images
```html
<img decoding="async" loading="lazy" src="URL" alt="replace text" height="42" width="42">
style/block（Styles/Sections）
<style type="text/css">
h1 {color:red;}
p {color:blue;}
</style>
<div>document in book</div>
<span>document in inline</span>
Disorder list
<ul>
    <li>Project</li>
    <li>Project</li>
</ul>
Sort list
<ol>
    <li>One</li>
    <li>Two</li>
</ol>
Custom list
<dl>
  <dt>project 1</dt>
    <dd>description 1</dd>
  <dt>project 2</dt>
    <dd>description 2</dd>
</dl>
``` 
## Tables
```html
<table border="1">
  <tr>
    <th>tableTitle</th>
    <th>tableTitle</th>
  </tr>
  <tr>
    <td>tableDate</td>
    <td>tableDate</td>
  </tr>
</table>
```
## Iframe
```html
<iframe src="demo_iframe.htm"></iframe>
```
## Forms
```html
<form action="demo_form.php" method="post/get">
<input type="text" name="email" size="40" maxlength="50">
<input type="password">
<input type="checkbox" checked="checked">
<input type="radio" checked="checked">
<input type="submit" value="Send">
<input type="reset">
<input type="hidden">
<select>
<option>orange</option>
<option selected="selected">banane</option>
<option>apple</option>
</select>
<textarea name="comment" rows="60" cols="20"></textarea>
</form>
```
## Entities
```html
&lt; same <
&gt; same >
&#169; same ©
```