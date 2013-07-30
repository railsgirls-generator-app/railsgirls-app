<h1>jQuery InstaSlider</h1>
A lightweight <em>(just 2kb when minified!)</em> jQuery image slider / carousel plugin that populates content from an Instagram hashtag or username.
<pre>
    .__                 __           _________.__  .__    .___            
    |__| ____   _______/  |______   /   _____/|  | |__| __| _/___________ 
    |  |/    \ /  ___/\   __\__  \  \_____  \ |  | |  |/ __ |/ __ \_  __ \
    |  |   |  \\___ \  |  |  / __ \_/ _____  \|  |_|  / /_/ \  ___/|  | \/
    |__|___|  /____  > |__| (____  /_______  /|____/__\____ |\___  >__|   
           \/     \/            \/        \/              \/    \/      
</pre>

<h2>Usage</h2>
<h3>HTML</h3>

<pre>
 &lt;div class="myslider"&gt;&lt;/div&gt;
</pre>

<h3>jQuery</h3>
<pre>
$('.myslider').instaSlider({
      clientID: 'your-id-here',
      access_token: 'your-access-token-here'
});
</pre>

<h3>CSS</h3>
This plugin can be fully customised using CSS. The default styling is provided below.
<pre>
.myslider{width:500px;height:500px;border:1px solid gray;margin:0 auto}
.instaslider-wrapper{width:500px;height:500px;background:#e7e7e7;overflow:hidden}
.instaslider-wrapper ul{width:10000px;list-style:none}
.instaslider-wrapper ul li{float:left}
div.error{width:100%;height:100%;background:rgba(0,0,0,0.6);color:#fff;font-family:arial;text-align:center}
div.error p{width:300px;line-height:180%;margin:0 auto;padding:167px 0 0}
.instaslider-wrapper ul li img{width:500px;height:auto}
.instaslider-nav{position:relative;top:-50%;margin:-50px 0 0}
.instaslider-nav .prev,.instaslider-nav .next{border:0;width:100px;height:100px;cursor:pointer;background:#072835;text-indent:-9999px}
.instaslider-nav .prev:hover{background-position:-2px -100px}
.instaslider-nav .next:hover{background-position:-98px -100px}
.instaslider-nav .prev{float:left;background:#072835 url(../img/arrow_sprite.png) 0 0}
.instaslider-nav .next{float:right;background:#072835 url(../img/arrow_sprite.png) -100px 0}
</pre>

<h2>Demo</h2>
<a href="http://iamchristill.com/plugins/instaslider/" target="_blank">http://iamchristill.com/plugins/instaslider/</a>

<h2>Default Options</h2>
These are the default options for the plugin that can be overridden.

<table>
<tr>
   <th>Option</th>
   <th>Default</th>
   <th>Required</th>
   <th>Type</th>
   <th>Description</th>
</tr>

<tr>
    <td>clientID</td>
    <td>null</td>
    <td>required</td>
   <td>string</td>
    <td>A clientID must be generated for this plugin to work. You can do this at <a href="http://instagram.com/developer/clients/register/">http://instagram.com/developer/clients/register/</a>.</td>
</tr>

<tr>
   <td>access_token</td>
<td>null</td>
<td>required</td>
<td>string</td>
<td>An access token is required for to be able to fetch data from a @username. This can be obtained at <a href="http://jelled.com/instagram/access-token">http://jelled.com/instagram/access-token</a>
</tr>

<tr>
    <td>search</td>
    <td>@iamchristill</td>
    <td>optional</td>
   <td>string</td>
    <td>An Instagram hashtag or username for plugin to fetch content from.</td>
</tr>

<tr>
    <td>prevClass</td>
    <td>prev</td>
    <td>optional</td>
   <td>string</td>
    <td>css class for 'previous' nav button.</td>
</tr>

<tr>
    <td>nextClass</td>
    <td>next</td>
    <td>optional</td>
   <td>string</td>
    <td>css class for 'next' nav button.</td>
</tr>

<tr>
    <td>limit</td>
    <td>5</td>
    <td>optional</td>
   <td>integer</td>
    <td>Allows for limiting the number of slides.</td>
</tr>

<tr>
    <td>Duration</td>
    <td>400</td>
    <td>optional</td>
   <td>integer</td>
    <td>Determines the duration of the slide animation.</td>
</tr>

<tr>
    <td>Auto</td>
    <td>true</td>
    <td>optional</td>
   <td>boolean</td>
    <td>If true, the slider will automatically slide.</td>
</tr>

<tr>
    <td>Delay</td>
    <td>5000</td>
    <td>optional</td>
   <td>integer</td>
    <td>Determines the delay before animating.</td>
</tr>

</table>
<br/>

<pre>
$('.myslider').instaSlider({
      clientID: null,
      access_token: null
      search: '@iamchristill',
      prevClass: 'prev',
      nextClass: 'next',
      limit: 5,
      duration: 1000,
      delay: 5000
});
</pre>

<h2>Dependencies</h2>
<ul>
<li><a href="http://jquery.com/">jQuery</a></li>
</ul>

<h2>Author</h2>
Chris Till - <a href="http://iamchristill.com" target="_blank">iamchristill.com</a>

<h2>Licence</h2>

<pre>
The MIT License (MIT)

InstaSlider © Chris Till 2013.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software 
and associated documentation files (the “Software”), 
to deal in the Software without restriction, including without limitation the rights to use, 
copy, modify, merge, publish, distribute, sublicense, 
and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, 
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of 
the Software
THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, 
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR 
ANY CLAIM, DAMAGES OR OTHER LIABILITY, 
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR 
THE USE OR OTHER DEALINGS IN THE SOFTWARE.
</pre>

<a href="http://mit-license.org/">http://mit-license.org/</a>

