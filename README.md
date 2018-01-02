# vertically-centering
Vertically centering objects in web design can cause excessive headaches. Here's how you can vertically center objects with ease using some simple HTML and default Bootstrap. 

## Tutorial

For detailed instruction's, view Solodev's [How to Vertically Center Elements with Bootstrap](http://origin.solodev.com/blog/web-design/how-to-vertically-center-elements-with-bootstrap.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/tatussmy/).

## HTML

The tutorial contains the following basic HTML markup.

```
<section class="section mt-5">
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <div>
          <img alt="Web Studio" class="img-fluid" src="https://www.solodev.com/core/fileparse.php/8/urlt/_/images/multiSite.jpg" />
        </div>
      </div>
      <div class="col-md-6 col-lg-5 ml-auto d-flex align-items-center mt-4 mt-md-0">
        <div>
          <h2>Module Studio</h2>
          <p class="margin-top-s">Whether you&rsquo;re a full stack web developer, content author, or business professional &ndash; Solodev gives you the power to build, customize, and manage modules to boost your website.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section mt-5">
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <div>
          <img alt="Web Studio" class="img-fluid" src="https://www.solodev.com/_/images/pageBuilderMagellan.jpg">
        </div>
      </div>
      <div class="col-md-6 col-lg-5 ml-auto d-flex align-items-center mt-4 mt-md-0">
        <div>
          <h2>Web Studio</h2>
          <p class="margin-top-s">Convert your web pages into reusable templates without your designs getting lost in space. Use drop zones to dynamically add content to your templates and speed up development time.</p>
        </div>
      </div>
    </div>
  </div>
</section>
```

## CSS

This tutorial requires no additional CSS

## JavaScript

This tutorial requires no additional JS

## External Resources

This tutorial includes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js"></script>
```

