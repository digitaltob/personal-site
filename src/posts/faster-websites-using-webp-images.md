---
title: Faster websites using WebP images 
date: '2020-07-20'
tags:
  - web performance
subheading: Google's WebP image format has a smaller file size compared to PNG and JPG helping your websites load faster. Learn why and how to implement it.
metaTitle: Faster websites using WebP images | Terry O'Brien 
metaDesc: The WebP image format has a smaller file size compared to PNG and JPG helping your websites load faster. Learn why and how to implement it.
socialImage: '/images/social-images/faster-websites-using-webp-images.png'
---

<p class="text-500 sm:text-600">In this article, I'll tell you more about WebP, why it's becoming more important and how to implement it on your website today. We should briefly touch on some of the benefits of a faster website before going into more detail about how WebP images can help.</p>

<h2>What are the benefits of a faster website?</h2>

<h3>Reduced bounce rate</h3>

The longer it takes for your web pages to load hurts your content, product or business you are trying to promote to the user. The moment the user clicks on a link to load the page they want to read, the clock is ticking. You need to serve that page to the user as quickly as possible. 

Research by Google has found <strong>as the page load time increases, the probability of bounce increases</strong>:
<blockquote>

As page load time goes from:

<p class="text-base sm:text-500 md:text-600"><strong>1s to 3s</strong> - the probability of bounce increases <strong>32%</strong>.<br>
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

<p class="text-base sm:text-500 md:text-600"><strong>"Looking at the 90th percentile of the distribution of page weight, images account for a whopping 5.2 MB of a roughly 7 MB page. In other words, images comprise almost 75% of the total page weight."</strong></p>

<p class="text-300"><a href="https://almanac.httparchive.org/en/2019/page-weight" target="_blank" rel="noreferrer noopener">HTTP Archive - Web Almanac 2019 - Page Weight Report</a>.</p>

</blockquote>

Optimizing images is one of the quickest wins to load webpages faster. 

You can optimize JPG and PNGs using compression tools such as <a href="https://tinypng.com/" target="_blank" rel="noreferrer noopener">TinyPNG (Online)</a>, <a href="https://imageoptim.com/" target="_blank" rel="noreferrer noopener">ImageOptim (Mac)</a>, <a href="https://nikkhokkho.sourceforge.io/static.php?page=FileOptimizer" target="_blank" rel="noreferrer noopener">FileOptimizer (Windows)</a> to reduce file sizes to a certain level, loading images quicker and using less bandwidth which is a great start.  

You can go even further using a newer image format designed for the web called WebP. 

<h2>What is WebP?</h2>

WebP is an image format <a href="https://developers.google.com/speed/webp" target="_blank" rel="noreferrer noopener">developed by Google back in 2010</a>. <strong>WebP provides better compression than JPG and PNG</strong>. It reduces file sizes with only minimal quality loss - so minimal that it's quite tricky to see visible differences when comparing with uncompressed images.

<img src="/images/imagery/webp-logo.png" width="600" height="196" alt="WebP logo"/>

WebP can handle different types of image usually best suited for either JPG or PNG under a single image format. We can briefly cover <strong>lossy</strong> versus <strong>lossless compression</strong> as WebP can do both and knowing the difference between the two will help you choose the best compression for the image you have.

<h3>What is lossy compression?</h3>

Lossy image compression is generally best suited for images/photographs with no transparency (like JPG). <strong>This process removes some data from the image, making little difference to the image visually</strong>.  Something to keep in mind with lossy is if you want to uncompress at a later point, you won't get the original quality back. I would advise the master/original images are backed-up before any compression for web use so this should not be an issue.

<h3>What is lossless compression?</h3>

Lossless image compression is best suited for images that are text-based, graphical-based, or have transparent backgrounds (like PNG, and GIF). <strong>Lossless doesn't remove the data in the image, only some metadata</strong> that is usually generated by the software or device that created the image/photo. It reduces the image without quality loss, and if uncompressed at a later date, quality is maintained.

<h2>Why use WebP?</h2>

Alongside Google's suite of websites (including YouTube), large sites like Amazon and Netflix also use WebP images. The main reason to use WebP is <strong>the smaller file size it produces compared to JPG and PNG</strong>. Meaning a lighter overall page size resulting in a faster page load. 

Google states:

<blockquote>

<p class="text-base sm:text-500 md:text-600"><strong>"WebP lossless images are 26% smaller in size compared to PNGs. WebP lossy images are 25-34% smaller than comparable JPEG images at equivalent SSIM quality index."</strong></p>

<p class="text-base sm:text-500 md:text-600"><strong>"Lossless WebP supports transparency (also known as alpha channel) at a cost of just 22% additional bytes. For cases when lossy RGB compression is acceptable, lossy WebP also supports transparency, typically providing 3× smaller file sizes compared to PNG."</strong></p>

<p class="text-300">Google Developers - <a href="https://developers.google.com/speed/webp" target="_blank" rel="noreferrer noopener">A new image format for the Web</a></p>

</blockquote>

Results like this translate into significant savings in your quest for faster loading web pages. 

<strong>These figures actually relate to <u>better</u> compression (over JPG and PNG)</strong>. 

Many images (of any format) on the web are unoptimized, so <strong>if you are compressing/optimizing images for the first time, there will be additional savings, sometimes significant</strong>.

Many developers will be aware of <a href="https://developers.google.com/web/tools/lighthouse" target="_blank" rel="noreferrer noopener">Lighthouse</a>, a Google tool for measuring page speed, giving a score out of 100. Lighthouse also suggests ways to speed up your web pages. Google uses page speed as a metric in search rankings. 

A measurement of a lighthouse test involves "use next-gen image formats". WebP is a next-gen image format, the only one with strong browser support.

<h2>Browser Support for WebP</h2>

While WebP has been around since 2010, it has taken some time for browser support for this image format to increase to a level where it can gain widespread adoption. 

As I write this, global WebP support is at 80% with Chrome, Firefox, and Edge all now supporting its use according to <a href="https://caniuse.com/#search=webp" target="_blank" rel="noreferrer noopener">CanIUse.com</a>. You may notice Safari's current versions are shown as red meaning WebP is not supported in version 13 and below. missing from that list.

<img src="/images/imagery/can-i-use-webp.png" width="1267" height="507" alt="WebP browser support from Can I Use website"/>

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

<img src="/images/imagery/squoosh-app.png" width="1000" height="657" alt="Screenshot of Squoosh App"/>

<h3>Using Sketch to convert to WebP</h3>

Sketch natively allows you to export an asset to WebP. To do this, select an asset on your design and in the Inspector panel on the right-hand side, open the 'Export' option. 

Here you can change the format to WebP. Then you can hit the 'Export selected....' button.

<img src="/images/imagery/sketch-export-webp-1.png" width="478" height="292" alt="WebP export settings in Sketch"/>

The file/folder 'Save as' dialogue window will appear, and you can adjust the WebP quality level. You will want to play with this depending on the image to determine the lowest quality level without any significant image deterioration.

<img src="/images/imagery/sketch-export-webp-2.png" width="748" height="114" alt="WebP export quality settings in Sketch"/>

<h3>Using Photoshop to convert to WebP</h3>

Unfortunately, Photoshop doesn't allow you to convert to WebP natively, but there are plugins to help do this. Download and install the <a href="http://telegraphics.com.au/sw/product/WebPFormat" target="_blank" rel="noreferrer noopener">Telegraphics WebP File Format plugin</a> and next time you are using Photoshop, using 'Save As...' you then have the options for saving with WebP and WebP Lossless with various settings to tweak depending on your choice.

<h3>Using Wordpress to convert to WebP</h3>

Currently, Wordpress does not support the WebP image format natively. It is still possible to load WebP images on your Wordpress website via a Wordpress plugin called <a href="https://en-gb.wordpress.org/plugins/webp-express/" target="_blank" rel="noreferrer noopener">WebP Express</a>.


<img src="/images/imagery/wordpress-webp-express.png" width="701" height="766" alt="WebP Express settings in Wordpress"/>

<h3>Using the command line to convert to WebP</h3>

You can use `cwebp` to convert image files to WebP via the command line. You'll need to download and install the <a href="https://developers.google.com/speed/webp/docs/precompiled" target="_blank" rel="noreferrer noopener">precomplied utilities</a> from the Google WebP Documentation site. The basic command would be:

<div class="full-bleed">

```javascript
cwebp -q 80 image.png -o image.webp
```

</div>

Read the <a href="https://developers.google.com/speed/webp/docs/cwebp" target="_blank" rel="noreferrer noopener">documentation on cwebp</a> to learn more.

<h3>Using other conversion methods</h3>

I can only cover a selection of conversion methods for the scope of this article. Depending on the operating system, content management system, build tools, or content delivery network (CDN) used, there are many options available to let you do this.

<h2>Using WebP in HTML</h2>

With the addition of WebP support in Safari browsers later this year, browser support will be high for WebP. Using WebP will be of benefit for the majority of users. 

There will be a portion of users who won't be able to see WebP images in their browser (IE11 and older versions of browsers slow to update). We need to add the WebP image but with a fallback image (JPG/PNG) for when the browser doesn't support it.

The requirement for a fallback image means a standard `<img>` element is not good enough in this case as it only gives the option of 1 image src, with no fallback.

<h3>Loading WebP Images with the &lt;picture&gt; element</h3>

To allow a fallback image, we can use the `<picture>` element as below:

<div class="full-bleed">

```html
<!-- Adding a WebP image with a fallback image -->
<picture>
    <source src="/images/example-image.webp" type="image/webp">
    <source src="/images/example-image.jpg" type="image/jpeg">
    <img src="/images/example-image.jpg">
</picture>
```

</div>

It will attempt to load the WebP image if the browser supports it. If not, it will fall back to second `<source>` element to load the JPG (or PNG). In the rare case the user has a old browser which doesn't even support the `<picture>` element it will fallback to the  `<img>` element, loading the JPG (or PNG) instead.

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

To help us do this, we need to set classes on the root `<html>` element. These classes will match a specific CSS rule to load the correct image based on browser support.

The two classes we'll use to help us do this are:

`.no-webp`

AND

`.web-p`

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

So to match one of these rules we will detect if the browser supports WebP, and from this, we decide which of the two 'root' classes (`.no-webp` or `.webp`) are dynamically added to the `<html>` element using javascript.

<h3>Detect if the browser supports WebP</h3>

<a href="https://modernizr.com/" target="_blank" rel="noreferrer noopener">Modernizr</a> is a javascript library which detects HTML5 and CSS3 features in the user's browser. It can be useful if you need to consider using fallbacks if you need to support older browsers. 

It is crucial if using javascript libraries only to use the features you need. Rather than loading in the full library which could be a large file, there is generally an option to selectively choose the features you require which results in a much smaller lightweight file. Remember, we are trying to speed up our website so the less we need to download to load the page, the better. Modernizr allows you to <a href="https://modernizr.com/download?webp-setclasses&q=webp" target="_blank" rel="noreferrer noopener">selectively choose the features</a> you need. 

For this example, you'll just need the 'Webp' feature.

<img src="/images/imagery/modernizr-webp.png" width="1385" height="984" alt="Modernizr select features"/>

When you add the script for the modernizr JS file to your HTML, you want it high up in your `<head>` section, so it has the chance to detect WebP support as soon as possible. This way, the correct background image can then be loaded.

I'm well aware this approach is dependent on javascript. While the web today is heavily reliant on javascript. A small number of users will have javascript disabled, and many websites will contain javascript errors which could affect the page from loading correctly.

So how do we cover occasions when javascript is disabled or not loaded for some reason?

When using modernizr, by default on the `<html>` element, we should add a `no-js` class directly in the code. 

<div class="full-bleed">

```html
<!-- Adding the default no-js class to the HTML element -->
<html lang="en" class="no-js">
```

</div>


If javascript is present, modernizr will swap this out to `js` and also add the additional classes required, in this case, either `web-p` or `no-webp`. 

Below is what the modernizr script does with the class attribute on the `<html>` element. In <strong>Chrome, which supports WebP</strong> (and its supporting WebP features), it dynamically updates to the below:

<div class="full-bleed">

```html
<!-- When Modernizr WebP script is added - CHROME (supports WebP) -->
<html lang="en" class="js webp webp-alpha webp-animation webp-lossless">
```

</div>

But if using a <strong>browser that doesn't support WebP, such as Safari 13</strong>, the code is dynamically updated to:

<div class="full-bleed">

```html
<!-- When Modernizr WebP script is added - SAFARI 13 (DOES NOT support WebP) -->
<html lang="en" class="js no-webp">
```

</div>

This is how we can target different classes via the CSS (referenced above) to load different CSS backgrounds.


If javascript is disabled (or there is a javascript error causing issues on the page), the hardcoded `no-js` class won't be dynamically changed. In this scenario, you can use this CSS rule below to continue to load the JPG/PNG instead:

<div class="full-bleed">

```css
/* No JS No Modernizr - load the png/jpg image */
.no-js .hero-container {
    background-image: url('/images/example-image.jpg');
}
```

</div>

One thing I'd recommend when adding this final `.no-js` CSS rule is to hold it in a separate CSS file to the rest of the CSS. Load this CSS file from within a `<noscript>` tag in the head as we only want this CSS (and the image) to be requested/loaded if javascript is disabled.

<h2>Conclusion</h2>

The WebP image format has <strong>better compression and optimization techniques</strong> than available with JPG and PNG formats. While <strong>fallbacks are still required for some older browsers</strong>, the <strong>benefit of switching to use WebP</strong> for the majority of your users will help page loads on your website which has the <strong>potential to decrease bounce rate, increase conversion, save money and even the environment</strong>. 

Large companies like Amazon and Netflix have moved to use WebP images alongside Google sites such as YouTube. Apple have decided 10 years after WebP was created that it is finally time to add it to its Safari browser for Mac and iOS later in 2020 - WebP isn't going anywhere. It is something you should consider to help improve your page speed scores which are becoming a stronger search ranking factor.

While <strong>switching to WebP</strong> images on existing large websites <strong>could involve significant work</strong>, there are ways to quickly serve WebP images with options on CDN services and specialist image CDNs. Content management systems such as WordPress have plugins available to help make the switch easier. <strong>Each situation will be different</strong> but there is no doubt, <strong>faster websites perform better</strong>. Image optimisation tends to be low hanging fruit in the quest for reducing page weights.

Will you be using the WebP image format?

