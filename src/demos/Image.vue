<template>
<xcontent>
  <span slot="title">Image</span>
<div class="container">
    <h1 class="title">Images</h1>
    <h2 class="subtitle">
      A container for <strong>responsive images</strong>
    </h2>

    <hr>

    <div class="content">
      <p>Because images can take a few seconds to load (or not at all), use the <code>.image</code> container to specify a <strong>precisely sized</strong> container so that your layout isn't broken because of image loading or image errors.</p>
    </div>

    <div class="example">
      <figure class="image is-128x128">
        <img src="http://placehold.it/128x128">
      </figure>
    </div>

<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;figure</span> <span class="na">class=</span><span class="s">"image is-128x128"</span><span class="nt">&gt;</span>
  <span class="nt">&lt;img</span> <span class="na">src=</span><span class="s">"http://placehold.it/128x128"</span><span class="nt">&gt;</span>
<span class="nt">&lt;/figure&gt;</span></code></pre><button class="copy">Copy</button></figure>

    <hr>

    <h3 class="title">Fixed square images</h3>
    <div class="content">
      <p>There are <strong>7</strong> dimensions to choose from, useful for <strong>avatars</strong>:</p>
    </div>

    <table class="table is-bordered">
      <tbody>
        <tr>
          <td><code>image is-16x16</code></td>
          <td><figure class="image is-16x16"><img src="http://placehold.it/16x16"></figure></td>
          <td>16x16px</td>
        </tr>
        <tr>
          <td><code>image is-24x24</code></td>
          <td><figure class="image is-24x24"><img src="http://placehold.it/24x24"></figure></td>
          <td>24x24px</td>
        </tr>
        <tr>
          <td><code>image is-32x32</code></td>
          <td><figure class="image is-32x32"><img src="http://placehold.it/32x32"></figure></td>
          <td>32x32px</td>
        </tr>
        <tr>
          <td><code>image is-48x48</code></td>
          <td><figure class="image is-48x48"><img src="http://placehold.it/48x48"></figure></td>
          <td>48x48px</td>
        </tr>
        <tr>
          <td><code>image is-64x64</code></td>
          <td><figure class="image is-64x64"><img src="http://placehold.it/64x64"></figure></td>
          <td>64x64px</td>
        </tr>
        <tr>
          <td><code>image is-96x96</code></td>
          <td><figure class="image is-96x96"><img src="http://placehold.it/96x96"></figure></td>
          <td>96x96px</td>
        </tr>
        <tr>
          <td><code>image is-128x128</code></td>
          <td><figure class="image is-128x128"><img src="http://placehold.it/128x128"></figure></td>
          <td>128x128px</td>
        </tr>
      </tbody>
    </table>

    <h4 class="title is-4">Retina images</h4>

    <div class="content">
      <p>Because the image is fixed in size, you can use an image that is <strong>twice as big</strong>. So for example, in a <code>128x128</code> container, you can use a <code>256x256</code> image, but resized to <strong>128x128</strong> pixels.</p>
    </div>

    <div class="example">
      <figure class="image is-128x128">
        <img src="http://placehold.it/256x256">
      </figure>
    </div>

<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;figure</span> <span class="na">class=</span><span class="s">"image is-128x128"</span><span class="nt">&gt;</span>
  <span class="nt">&lt;img</span> <span class="na">src=</span><span class="s">"http://placehold.it/256x256"</span><span class="nt">&gt;</span>
<span class="nt">&lt;/figure&gt;</span></code></pre><button class="copy">Copy</button></figure>

    <hr>

    <h3 class="title">Responsive images with ratios</h3>

    <div class="content">
      <p>If you don't know the exact dimensions but know the <strong>ratio</strong> instead, you can use one of the <strong>5 ratio modifers</strong>:</p>
    </div>

    <table id="images" class="table is-bordered">
      <tbody>
        <tr>
          <td><code>image is-square</code></td>
          <td><figure class="image is-square"><img src="http://placehold.it/480x480"></figure></td>
          <td>Square (or 1by1)</td>
        </tr>
        <tr>
          <td><code>image is-1by1</code></td>
          <td><figure class="image is-1by1"><img src="http://placehold.it/480x480"></figure></td>
          <td>1 by 1</td>
        </tr>
        <tr>
          <td><code>image is-4by3</code></td>
          <td><figure class="image is-4by3"><img src="http://placehold.it/640x480"></figure></td>
          <td>4 by 3</td>
        </tr>
        <tr>
          <td><code>image is-3by2</code></td>
          <td><figure class="image is-3by2"><img src="http://placehold.it/480x320"></figure></td>
          <td>3 by 2</td>
        </tr>
        <tr>
          <td><code>image is-16by9</code></td>
          <td><figure class="image is-16by9"><img src="http://placehold.it/640x360"></figure></td>
          <td>16 by 9</td>
        </tr>
        <tr>
          <td><code>image is-2by1</code></td>
          <td><figure class="image is-2by1"><img src="http://placehold.it/640x320"></figure></td>
          <td>2 by 1</td>
        </tr>
      </tbody>
    </table>

    <div class="content">
      <p>The <code>.image</code> container will take up the <strong>whole width</strong> while maintaining the perfect ratio.</p>
    </div>
  </div>
</xcontent>
</template>
<script>
import { Xcontent } from '../components/page'
export default {
  components: {
    Xcontent
  }
}
</script>