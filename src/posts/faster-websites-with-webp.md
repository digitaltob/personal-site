---
title: Faster websites with WebP
date: '2020-07-12'
tags:
  - page speed
  - optimisation
  - web performance
subheading: With growing support for Google's WebP image format and its smaller file size compared to PNG and JPG, is it now time for widespread adoption?
---

<p class="text-600">In this article, I'll tell you more about WebP, why it's becoming more important and how to implement it on your website today. We should briefly touch on some of the benefits of a faster website before going into more detail about how WebP images can help.</p>

<h2>What are the benefits of a faster website?</h2>

<h3>Reduced bounce rate</h3>

The longer it takes for your web pages to load hurts your content, product or business you are trying to promote to the user. The moment the user clicks on a link to load the page they want to read, the clock is ticking. You need to serve that page to the user as quickly as possible. 

Research by Google has found <strong>as the page load time increases, the probability of bounce increases</strong>:
<blockquote>

As page load time goes from:

<p class="text-600"><strong>1s to 3s</strong> - the probability of bounce increases <strong>32%</strong>.<br>
<strong>1s to 5s</strong> - the probability of bounce increases <strong>90%</strong>.<br>
<strong>1s to 6s</strong> - the probability of bounce increases <strong>106%</strong>.<br>
<strong>1s to 10s</strong> - the probability of bounce increases <strong>123%</strong>.</p>

<p class="text-300">Think with Google - <a href="https://www.thinkwithgoogle.com/marketing-resources/data-measurement/mobile-page-speed-new-industry-benchmarks/" target="_blank" rel="noreferrer noopener">Google/SOASTA Research 2017</a></p>

</blockquote>

<h3>Helps search rankings</h3>

Google has stated that <a href="https://webmasters.googleblog.com/2018/01/using-page-speed-in-mobile-search.html" target="_blank" rel="noreferrer noopener">page speed is a ranking factor</a>. They have various tools to measure page speeds and are also introducing additional ranking factors that bring <a href="https://webmasters.googleblog.com/2020/05/evaluating-page-experience.html" target="_blank" rel="noreferrer noopener">page speed and user experience stats together</a>. 

<h3>Bandwidth savings</h3>

Not everyone has a fast internet connection. Users on cellular connections or slower connections, including those in developing countries would appreciate not having to download unnecessary data to view web pages. Also, in some cases, businesses can make significant savings on server costs by reducing the amount of bandwidth used.

<h3>Good for the environment</h3>

A faster website uses less power on the user device, the webserver and across the network, producing fewer CO2 emissions.

<h2>Why are images an important factor for page speeds?</h2>

Unoptimized images tend to be the <strong>most significant contributor to page bloat</strong>. 

<blockquote>

HTTP Archive's 2019 Web Almanac (which highlights the 'state of the web' from evaluating millions of web pages) states:

<p class="text-600"><strong>"Looking at the 90th percentile of the distribution of page weight, images account for a whopping 5.2 MB of a roughly 7 MB page. In other words, images comprise almost 75% of the total page weight."</strong></p>

<p class="text-300"><a href="https://almanac.httparchive.org/en/2019/page-weight" target="_blank" rel="noreferrer noopener">HTTP Archive - Web Almanac 2019 - Page Weight Report</a>.</p>

</blockquote>

Optimizing images is one of the quickest wins to load webpages faster. 

You can optimize JPG and PNGs using compression tools such as <a href="https://tinypng.com/" target="_blank" rel="noreferrer noopener">TinyPNG (Online)</a>, <a href="https://imageoptim.com/" target="_blank" rel="noreferrer noopener">ImageOptim (Mac)</a>, <a href="https://nikkhokkho.sourceforge.io/static.php?page=FileOptimizer" target="_blank" rel="noreferrer noopener">FileOptimizer (Windows)</a> to reduce file sizes to a certain level, loading images quicker and using less bandwidth which is a great start.  

You can go even further using a newer image format designed for the web called WebP. 

<h2>What is WebP?</h2>

WebP is an image format <a href="https://developers.google.com/speed/webp" target="_blank" rel="noreferrer noopener">developed by Google back in 2010</a>. <strong>WebP provides better compression than JPG and PNG</strong>. It reduces file sizes with only minimal quality loss - so minimal that it's quite tricky to see visible differences when comparing with uncompressed images.

Now is a good time to explain briefly <strong>lossy</strong> versus <strong>lossless compression</strong> as WebP can do both and knowing the difference between the two will help you choose the best compression for the image you have.

<h3>What is lossy compression?</h3>

Lossy image compression is generally best suited for images/photographs with no transparency (like JPG). <strong>This process removes some data from the image, making little difference to the image visually</strong>.  Something to keep in mind with lossy is if you want to uncompress at a later point, you won't get the original quality back. I would advise the master/original images are backed-up before any compression for web use so this should not be an issue.

<h3>What is lossless compression?</h3>

Lossless image compression is best suited for images that are text-based, graphical-based, or have transparent backgrounds (like PNG, and GIF). <strong>Lossless doesn't remove the data in the image, only some metadata</strong> that is usually generated by the software or device that created the image/photo. It reduces the image without quality loss, and if uncompressed at a later date, quality is maintained.

<h2>Why use WebP?</h2>

The main reason to use WebP is <strong>the smaller file size it produces compared to JPG and PNG</strong>. Meaning a lighter overall page size resulting in a faster page load. 

Google states:

<blockquote>

<p class="text-600"><strong>"WebP lossless images are 26% smaller in size compared to PNGs. WebP lossy images are 25-34% smaller than comparable JPEG images at equivalent SSIM quality index."</strong></p>

<p class="text-600"><strong>"Lossless WebP supports transparency (also known as alpha channel) at a cost of just 22% additional bytes. For cases when lossy RGB compression is acceptable, lossy WebP also supports transparency, typically providing 3× smaller file sizes compared to PNG."</strong></p>

<p class="text-300">Google Developers - <a href="https://developers.google.com/speed/webp" target="_blank" rel="noreferrer noopener">A new image format for the Web</a></p>

</blockquote>

Results like this translate into significant savings in your quest for faster loading web pages. 

<strong>These figures actually relate to <u>better</u> compression (over JPG and PNG)</strong>. 

<strong>Many images (of any format) on the web are unoptimized, so if you are compressing/optimizing images for the first time, there will be additional savings, sometimes significant</strong>.

<h3>Images on this page - An experiment</h3>

While putting this article together, I thought I'd carry out an experiment. There are a number of images in this article and 


Many developers will be aware of Lighthouse, a Google tool for measuring page speed, giving a score out of 100. Lighthouse also suggests ways to speed up your web pages. Google uses page speed as a metric in search rankings. 

A measurement of a lighthouse test involves "use next-gen image formats". WebP is a next-gen image format, the only one with strong browser support.

<h2>Browser Support for WebP</h2>

While WebP has been around since 2010, it has taken some time for browser support for this image format to increase to a level where it can gain widespread adoption. 

As I write this, global WebP support is at 78% (check current stats) with Chrome, Firefox, and Edge all now supporting its use. You may notice Safari is missing from that list.

(Show Can I Use)

<h2>When will Safari support WebP?</h2>

In June 2020 at Apple's WWDC event, it was announced that <a href="https://developer.apple.com/documentation/safari-release-notes/safari-14-beta-release-notes" target="_blank" rel="noreferrer noopener">Safari 14 (currently in beta)</a>, will support WebP images. Safari 14 will be released for both Mac and iOS later in the year, most likely September - based on major Safari updates released in recent years.

Browser support will increase driving wider adoption of this image format on the web.

<h2>Will IE11 support WebP?</h2>

IE11 is unlikely to support WebP. While this could be an issue depending on your analytics of browser usage for your website(s), I will explain later in the article how you can still serve WebP images with a fallback for older browsers such as IE11.

So, should you use WebP images instead of JPG and PNG?

Now is a great time to consider using WebP for your websites. WebP support will increase to 80-90% of users (on average globally) when Safari 14 is released later this year. Yes, a fallback will still be required, but the savings you'll make to make pages load faster will be worth the effort.

<h2>How to convert JPG and PNG to WebP?</h2>

Converting JPGs and PNGs to WebP can be done in several ways with varying levels of difficulty. I'll share several options that will suit designers, developers and content editors depending on how they source their images and add them to websites. 

<h3>Convert online using Squoosh.app</h3>

Squoosh.app is a web app produced by Google. It's an easy and quick way to convert your PNG and JPG images to WebP (and many other image formats). There are several controls to tweak settings, including a small slider to adjust the quality and on the image preview itself a larger slider to compare quality with the original image.

<div class="full-bleed">
<iframe width="560" height="315" src="https://www.youtube.com/embed/4jPwanaGnfQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

Advantages, easy process, visual
Disadvantages, one image at a time

<h3>Using Sketch to convert to WebP</h3>

Sketch natively allows you to export an asset to WebP. To do this, select an asset on your design and in the Inspector panel on the right-hand side, open the 'Export' option. 

(Screenshot of Export)

Here you can change the format to WebP. Then you can hit the 'Export selected....' button.

(Screen of quality setting)

The file/folder 'Save as' dialogue window will appear, and you can adjust the WebP quality level. You will want to play with this depending on the image to determine the lowest quality level without any significant image deterioration.

<h3>Using Photoshop to convert to WebP</h3>

Unfortunately, Photoshop doesn't allow you to convert to WebP natively, but there are plugins to help do this. Download and install the Telegraphics WebP File Format plugin and next time you are using Photoshop, using 'Save As...' you then have the options for saving with WebP and WebP Lossless with various settings to tweak depending on your choice.

<h3>Using Wordpress to convert to WebP</h3>

Currently, Wordpress does not support the WebP image format natively. It is still possible to load WebP images on your Wordpress website via a Wordpress plugin called WebP Express.

(Add image)

<h3>Using the command line to convert to WebP</h3>

<h3>Using other conversion methods</h3>

I can only cover a selection of conversion methods for the scope of this article. Depending on the operating system, content management system, build tools, or content delivery network (CDN) used, there are many options available to let you do this.

<h2>Using WebP in HTML</h2>

With the addition of WebP support in Safari browsers later this year, browser support will be high for WebP. Using WebP will be of benefit for the majority of users. 

There will be a portion of users who won't be able to see WebP images in their browser (IE11 and older versions of browsers slow to update). We need to add the WebP image but with a fallback image (JPG/PNG) for when the browser doesn't support it.

The requirement for a fallback image means a standard &lt;img&gt; element is not good enough in this case as it only gives the option of 1 image src, with no fallback.

<h3>Loading WebP Images with the &lt;picture&gt; element</h3>

To allow a fallback image, we can use the &lt;picture&gt; element as below:

(CODE)

It will attempt to load the WebP image if the browser supports it. If not, it will fall back to the &lt;img&gt; element, loading the JPG/PNG instead.

<h2>Using WebP in CSS Backgrounds</h2>

Loading WebP background images via CSS involves more effort to set up (to ensure a fallback image when not supported), but don't let this discourage you. The time you spend to set this up will be worth the benefit of having a faster website. Let's go over how to set this up.

With CSS, we would normally load a background image in like below:

<div class="full-bleed">

```css
/* Adding a WebP image in CSS - if no fallback considered */
 .hero-container {
    background-image: url('/images/example-image.webp');
}
```

</div>

Now because not all browsers support WebP, this line of code would load no background image for this element in those affected browsers. We need a way to choose between 2 different images via CSS, for example, a WebP image or a JPG image. 

We can do this by detecting if the browser supports WebP. If it does we load the WebP background image, if not, we can load the fallback image - in this example, a JPG image.

To help us do this, we need to set classes on the root &lt;html&gt; element. These classes will match a specific CSS rule to load the correct image based on browser support.

The two classes we'll use to help us do this are:

.no-webp
AND
.web-p

We'll only add one of these classes to the code, we'll cover how we add this into the code in a moment, firstly, lets set up the two different CSS rules we need:

<div class="full-bleed">

```css
/* No WebP support - load the png/jpg image - the fallback */
.no-webp .hero-container {
    background-image: url('/images/example-image.jpg');
}
```

</div>
<div class="full-bleed">

```css
/* WebP supported - load the faster WebP image instead */
.web-p .hero-container {
    background-image: url('/images/example-image.webp');
}
```

</div>

So to match one of these rules we will detect if the browser supports WebP, and from this, we decide which of the two 'root' classes (.no-webp or .webp) are dynamically added to the &lt;html&gt; element using javascript.

<h3>Detect if the browser supports WebP</h3>
 
<h4>Via a detection library - Modernizr</h4>

Modernizr is a javascript library which detects HTML5 and CSS3 features in the user's browser. It can be useful if you need to consider using fallbacks if you need to support older browsers. 

It is crucial if using javascript libraries only to use the features you need. Rather than loading in the full library which could be a large file, there is generally an option to selectively choose the features you require which results in a much smaller lightweight file. Remember, we are trying to speed up our website so the less we need to download to load the page, the better.

(MODERNIZR SCREENSHOT BROWSE)

When you add the script for the modernizr JS file to your HTML, you want to high up in your &lt;head&gt; section, so it has the chance to detect WebP support as soon as possible. This way, the correct background image can then be loaded.

I've well aware this approach is dependent on javascript. While the web today is heavily reliant on javascript, it is worth taking a moment to highlight that not all users will have javascript enabled. This post from [ WEBSITE HERE ] explains why.

So how do we cover occasions when javascript is disabled on not loaded for some reason?

When using modernizr, by default on the &lt;html&gt; element, we should add a 'no-js' class directly in the code. If javascript is present, modernizr will swap this out to 'js' and also add the additional classes required, in this case, either 'web-p' or 'no-webp'. So we know that if javascript is disabled, the hardcoded 'no-js' class won't be dynamically changed. In this scenario, you can use this CSS rule below to continue to load the JPG/PNG instead:

<div class="full-bleed">

```css
/* No JS No Modernizr - load the png/jpg image */
.no-js .hero-container {
    background-image: url('/images/example-image.jpg');
}
```

</div>

One thing I'd recommend when adding this .no-js CSS rule is to hold it in a separate CSS file to the rest of the CSS. Load this CSS file from within a &lt;noscript&gt; tag in the head as we only want this CSS (and the image) to be requested/loaded if javascript is disabled.

<h2>Conclusion</h2>

The WebP image format is the

