# quote-overlays
Showcasing your service or product is an absolute given on most websites. Often, this presentation can come in the mold of customer or client quotes. By providing direct quotes from actual customers, you legitimize your brand while simulatenously displaying an actual use-case where your product/service was a distinct solution.

In this article we provide code and instruct you on how to add a customer quotes as overlays on top of a client logo.
## Tutorial

For detailed instructions, view Solodev's [Creating Customer Quote Overlays](https://www.solodev.com/blog/web-design/creating-customer-quote-overlays.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/k6L11qsp/).

## HTML

The quote overlays need the following HTML markup.
```
<div class="container-fluid">

  <div onclick="" class="col-md-3 col-sm-4 col-xs-6 overlay-box box1">
    <div class="overlay-content text-center" style="padding-top: 71.5px;">
      <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor."</p>
      <a href="#" class="btn btn-grey">View Case Study</a>
    </div>
    <div class="overlay-logo"></div>
  </div>
  
  <div onclick="" class="col-md-3 col-sm-4 col-xs-6 overlay-box box2">
    <div class="overlay-content text-center" style="padding-top: 71.5px;">
      <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor."</p>
      <a href="#" class="btn btn-grey">View Case Study</a>
    </div>
    <div class="overlay-logo"></div>
  </div>
  
  <div onclick="" class="col-md-3 col-sm-4 col-xs-6 overlay-box box3">
    <div class="overlay-content text-center" style="padding-top: 71.5px;">
      <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor."</p>
      <a href="#" class="btn btn-grey ">View Case Study</a>
    </div>
    <div class="overlay-logo"></div>
  </div>

  <div onclick="" class="col-md-3 col-sm-4 col-xs-6 overlay-box box4">
    <div class="overlay-content text-center" style="padding-top: 71.5px;">
      <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor."</p>
      <a href="#" class="btn btn-grey">View Case Study</a>
    </div>
    <div class="overlay-logo"></div>
  </div>
  
  <div onclick="" class="col-md-3 col-sm-4 col-xs-6 overlay-box box5">
    <div class="overlay-content text-center" style="padding-top: 71.5px;">
      <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor."</p>
      <a href="#" class="btn btn-grey">View Case Study</a>
    </div>
    <div class="overlay-logo"></div>
  </div>
  
  <div onclick="" class="col-md-3 col-sm-4 col-xs-6 overlay-box box6">
    <div class="overlay-content text-center" style="padding-top: 71.5px;">
      <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor."</p>
      <a href="#" class="btn btn-grey">View Case Study</a>
    </div>
    <div class="overlay-logo"></div>
  </div>
  
  <div onclick="" class="col-md-3 col-sm-4 col-xs-6 overlay-box box7">
    <div class="overlay-content text-center" style="padding-top: 71.5px;">
      <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor."</p>
      <a href="#" class="btn btn-grey">View Case Study</a>
    </div>
    <div class="overlay-logo"></div>
  </div>
  
  <div onclick="" class="col-md-3 col-sm-4 col-xs-6 overlay-box box8">
    <div class="overlay-content text-center" style="padding-top: 71.5px;">
      <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor."</p>
      <a href="#" class="btn btn-grey">View Case Study</a>
    </div>
    <div class="overlay-logo"></div>
  </div>
  
  <div onclick="" class="col-md-3 col-sm-4 col-xs-6 overlay-box box9">
    <div class="overlay-content text-center" style="padding-top: 71.5px;">
      <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor."</p>
      <a href="#" class="btn btn-grey">View Case Study</a>
    </div>
    <div class="overlay-logo"></div>
  </div>
  
  <div onclick="" class="col-md-3 col-sm-4 col-xs-6 overlay-box box10">
    <div class="overlay-content text-center" style="padding-top: 71.5px;">
      <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor."</p>
      <a href="#" class="btn btn-grey">View Case Study</a>
    </div>
    <div class="overlay-logo"></div>
  </div>
  
  <div onclick="" class="col-md-3 col-sm-4 col-xs-6 overlay-box box11">
    <div class="overlay-content text-center" style="padding-top: 71.5px;">
      <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor."</p>
      <a href="#" data-video-id="139255589">see the video</a>
    </div>
    <div class="overlay-logo"></div>
  </div>
  
  <div onclick="" class="col-md-3 col-sm-4 col-xs-6 overlay-box box12">
    <div class="overlay-content text-center" style="padding-top: 71.5px;">
      <p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor."</p>
      <a href="#" class="btn btn-grey">View Case Study</a>
    </div>
    <div class="overlay-logo"></div>
  </div>
             
</div>
```
## CSS

All required CSS is in quote-overlay.css

## External Includes

This tutorial includes the following third party resources.
```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```

