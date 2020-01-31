<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="CSS_Media_Query_0"></a>CSS Media Query :computer: :iphone:</h1>
<blockquote>
<h4 class="code-line" data-line-start=2 data-line-end=3 ><a id="CSS_media_queries_allow_us_to_adjust_the_display_and_orientation_of_content_at_different_screen_sizes_2"></a>CSS media queries allow us to adjust the display and orientation of content at different screen sizes.</h4>
</blockquote>
<p class="has-line-data" data-line-start="6" data-line-end="8">Device = Most of the Smartphones Mobiles (Portrait)<br>
Screen = 320px to 479px</p>
<pre><code> @media (min-width: 320px) and (max-width: 480px) {


}
</code></pre>
<p class="has-line-data" data-line-start="14" data-line-end="16">Device = Low Resolution Tablets, Mobiles (Landscape)<br>
Screen = 481px to 767px</p>
<pre><code>@media (min-width: 481px) and (max-width: 767px) {


}
</code></pre>
<p class="has-line-data" data-line-start="22" data-line-end="24">Device = Tablets, Ipads (landscape)<br>
Screen = 768px to 1024px</p>
<pre><code>@media (min-width: 768px) and (max-width: 1024px) and (orientation: landscape) {


}
</code></pre>
<p class="has-line-data" data-line-start="30" data-line-end="32">Device = Tablets, Ipads (portrait)<br>
Screen =  768px to 1024px</p>
<pre><code>@media (min-width: 768px) and (max-width: 1024px) {


}
</code></pre>
<p class="has-line-data" data-line-start="38" data-line-end="40">Device = Laptops, Desktops<br>
Screen = 1025px to 1280px</p>
<pre><code> @media (min-width: 1025px) and (max-width: 1280px) {


}
</code></pre>
<p class="has-line-data" data-line-start="46" data-line-end="48">Device = Desktops<br>
Screen = 1281px to higher resolution desktops</p>
<pre><code>@media (min-width: 1281px) {

}
</code></pre>
