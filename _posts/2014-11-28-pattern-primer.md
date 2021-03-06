---
layout: post
title: Site Style & Patterns
description: "Little snippets of markup saved to in a patterns gallery."
---
<!DOCTYPE html>
<head>
<meta charset="utf-8">
<title>Pattern Primer</title>
<link rel="stylesheet" href="global.css">
<style>
.pattern {
    clear: both;
    overflow: hidden;
}
.pattern .display {
    width: 65%;
    float: left;
}
.pattern .source {
    width: 30%;
    float: right;
}
.pattern .source textarea {
    width: 90%;
}
</style>
</head>
<body><div class="pattern"><div class="display"><blockquote>
<p>This text is quoted. A block of quoted text like this is particularly useful when presented as a pull-quote within an article of text.</p>
</blockquote></div><div class="source"><textarea rows="6" cols="30">&lt;blockquote>
&lt;p>This text is quoted. A block of quoted text like this is particularly useful when presented as a pull-quote within an article of text.&lt;/p>
&lt;/blockquote></textarea></div></div><div class="pattern"><div class="display"><div class="feedback error">
<p>This is an error feedback message.</p>
</div></div><div class="source"><textarea rows="6" cols="30">&lt;div class=&quot;feedback error&quot;>
&lt;p>This is an error feedback message.&lt;/p>
&lt;/div></textarea></div></div><div class="pattern"><div class="display"><div class="feedback">
<p>This is a feedback message for the user.</p>
</div></div><div class="source"><textarea rows="6" cols="30">&lt;div class=&quot;feedback&quot;>
&lt;p>This is a feedback message for the user.&lt;/p>
&lt;/div></textarea></div></div><div class="pattern"><div class="display"><button>Button element</button>


<input type="submit" value="Submit button"></div><div class="source"><textarea rows="6" cols="30">&lt;button>Button element&lt;/button>


&lt;input type=&quot;submit&quot; value=&quot;Submit button&quot;></textarea></div></div><div class="pattern"><div class="display"><label><input type="checkbox"> Label text</label></div><div class="source"><textarea rows="6" cols="30">&lt;label>&lt;input type=&quot;checkbox&quot;> Label text&lt;/label></textarea></div></div><div class="pattern"><div class="display"><label>Label text</label>
<input type="email"></div><div class="source"><textarea rows="6" cols="30">&lt;label>Label text&lt;/label>
&lt;input type=&quot;email&quot;></textarea></div></div><div class="pattern"><div class="display"><label>Label text</label>
<input type="number"></div><div class="source"><textarea rows="6" cols="30">&lt;label>Label text&lt;/label>
&lt;input type=&quot;number&quot;></textarea></div></div><div class="pattern"><div class="display"><select>
<option>option text</option>
</select></div><div class="source"><textarea rows="6" cols="30">&lt;select>
&lt;option>option text&lt;/option>
&lt;/select></textarea></div></div><div class="pattern"><div class="display"><label>Label text</label>
<input type="text"></div><div class="source"><textarea rows="6" cols="30">&lt;label>Label text&lt;/label>
&lt;input type=&quot;text&quot;></textarea></div></div><div class="pattern"><div class="display"><label>Label text</label>
<textarea rows="5" cols="20"></textarea></div><div class="source"><textarea rows="6" cols="30">&lt;label>Label text&lt;/label>
&lt;textarea rows=&quot;5&quot; cols=&quot;20&quot;>&lt;/textarea></textarea></div></div><div class="pattern"><div class="display"><label>Label text</label>
<input type="url"></div><div class="source"><textarea rows="6" cols="30">&lt;label>Label text&lt;/label>
&lt;input type=&quot;url&quot;></textarea></div></div><div class="pattern"><div class="display"><h1>Level one heading</h1></div><div class="source"><textarea rows="6" cols="30">&lt;h1>Level one heading&lt;/h1></textarea></div></div><div class="pattern"><div class="display"><h2>Level two heading</h2></div><div class="source"><textarea rows="6" cols="30">&lt;h2>Level two heading&lt;/h2></textarea></div></div><div class="pattern"><div class="display"><h3>Level three heading</h3></div><div class="source"><textarea rows="6" cols="30">&lt;h3>Level three heading&lt;/h3></textarea></div></div><div class="pattern"><div class="display"><h4>Level four heading</h4></div><div class="source"><textarea rows="6" cols="30">&lt;h4>Level four heading&lt;/h4></textarea></div></div><div class="pattern"><div class="display"><h5>Level five heading</h5></div><div class="source"><textarea rows="6" cols="30">&lt;h5>Level five heading&lt;/h5></textarea></div></div><div class="pattern"><div class="display"><h6>Level six heading</h6></div><div class="source"><textarea rows="6" cols="30">&lt;h6>Level six heading&lt;/h6></textarea></div></div><div class="pattern"><div class="display"><ol>
<li>First list item</li>
<li>Second item in a list of ordered items</li>
<li>Third item in the list</li>
</ol>
</div><div class="source"><textarea rows="6" cols="30">&lt;ol>
&lt;li>First list item&lt;/li>
&lt;li>Second item in a list of ordered items&lt;/li>
&lt;li>Third item in the list&lt;/li>
&lt;/ol>
</textarea></div></div><div class="pattern"><div class="display"><ul>
<li>A list item</li>
<li>Another item in a list</li>
<li>Yet another item in this list of items</li>
</ul></div><div class="source"><textarea rows="6" cols="30">&lt;ul>
&lt;li>A list item&lt;/li>
&lt;li>Another item in a list&lt;/li>
&lt;li>Yet another item in this list of items&lt;/li>
&lt;/ul></textarea></div></div><div class="pattern"><div class="display"><ol class="pagination">
<li><a>1</a></li>
<li><a href="#">2</a></li>
<li><a href="#">3</a></li>
<li><a href="#">4</a></li>
<li><a href="#">5</a></li>
<li><a href="#">6</a></li>
<li><a href="#">7</a></li>
<li><a href="#">8</a></li>
<li><a href="#">9</a></li>
<li><a href="#">10</a></li>
</ol></div><div class="source"><textarea rows="6" cols="30">&lt;ol class=&quot;pagination&quot;>
&lt;li>&lt;a>1&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>2&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>3&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>4&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>5&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>6&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>7&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>8&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>9&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>10&lt;/a>&lt;/li>
&lt;/ol></textarea></div></div><div class="pattern"><div class="display"><ol class="pagination">
<li><a href="#">1</a></li>
<li><a href="#">2</a></li>
<li><a href="#">3</a></li>
<li><a href="#">4</a></li>
<li><a href="#">5</a></li>
<li><a href="#">6</a></li>
<li><a href="#">7</a></li>
<li><a href="#">8</a></li>
<li><a href="#">9</a></li>
<li><a>10</a></li>
</ol></div><div class="source"><textarea rows="6" cols="30">&lt;ol class=&quot;pagination&quot;>
&lt;li>&lt;a href=&quot;#&quot;>1&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>2&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>3&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>4&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>5&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>6&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>7&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>8&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>9&lt;/a>&lt;/li>
&lt;li>&lt;a>10&lt;/a>&lt;/li>
&lt;/ol></textarea></div></div><div class="pattern"><div class="display"><ol class="pagination">
<li><a href="#">1</a></li>
<li><a href="#">2</a></li>
<li><a href="#">3</a></li>
<li><a href="#">4</a></li>
<li><a>5</a></li>
<li><a href="#">6</a></li>
<li><a href="#">7</a></li>
<li><a href="#">8</a></li>
<li><a href="#">9</a></li>
<li><a href="#">10</a></li>
</ol></div><div class="source"><textarea rows="6" cols="30">&lt;ol class=&quot;pagination&quot;>
&lt;li>&lt;a href=&quot;#&quot;>1&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>2&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>3&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>4&lt;/a>&lt;/li>
&lt;li>&lt;a>5&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>6&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>7&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>8&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>9&lt;/a>&lt;/li>
&lt;li>&lt;a href=&quot;#&quot;>10&lt;/a>&lt;/li>
&lt;/ol></textarea></div></div><div class="pattern"><div class="display"><p>This is a paragraph of text. Some of the text may be <em>emphasised</em> and some it might even be <strong>strongly emphasised</strong>. Occasionally <q>quoted text</q> may be found within a paragraph &hellip;and of course <a href="#">a link</a> may appear at any point in the text. The average paragraph contains five or six sentences although some may contain as little or one or two while others carry on for anything up to ten sentences and beyond.</p></div><div class="source"><textarea rows="6" cols="30">&lt;p>This is a paragraph of text. Some of the text may be &lt;em>emphasised&lt;/em> and some it might even be &lt;strong>strongly emphasised&lt;/strong>. Occasionally &lt;q>quoted text&lt;/q> may be found within a paragraph &amp;hellip;and of course &lt;a href=&quot;#&quot;>a link&lt;/a> may appear at any point in the text. The average paragraph contains five or six sentences although some may contain as little or one or two while others carry on for anything up to ten sentences and beyond.&lt;/p></textarea></div></div></body></html>

