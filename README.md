# jQuery Honeycombs
jQuery plugin for displaying images in a responsive Honeycomb/ Hexagon grid with caption and anchor

## Demo
Open the following link to check the demo.

Demo URL: https://nasirkhan.github.com/honeycombs

## Honeycomb/ Hexagon Grid
To create a Honeycomb/ Hegagon grid, use the following HTML markup:

```HTML
<div class="honeycombs">
    <div class="comb">
      <img src="https://farm6.staticflickr.com/5737/31044656732_c031f1294c_z.jpg" /> 
    </div>
    <div class="comb">
      <img src="https://farm6.staticflickr.com/5727/30785062315_cb44d0c372_z.jpg" /> 
    </div>
    <div class="comb">
      <img src="https://farm8.staticflickr.com/7091/27557985951_7abf426c1e_z.jpg" /> 
    </div>
</div>
```

Add the following Javascript snippet at the bottom of the page,

```js
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="homeycombs/js/jquery.homeycombs.js"></script>

<script type="text/javascript">
    $(document).ready(function () {
        $('.honeycombs').honeycombs();
    });
</script>
```

## Honeycomb/ Hexagon Grid With Caption
To create a Honeycomb/ Hegagon grid, use the following HTML markup:

```HTML
<div class="honeycombs">
    <div class="comb">
      <img src="https://farm6.staticflickr.com/5737/31044656732_c031f1294c_z.jpg" />
      <span>
        <br>
        jQuery Honeycombs
      </span>
    </div>

    <div class="comb">
      <img src="https://farm6.staticflickr.com/5727/30785062315_cb44d0c372_z.jpg" /> 
        <span>
            <b>Image</b>
            <br>Caption
        </span>
    </div>

    <div class="comb">
      <img src="https://farm8.staticflickr.com/7091/27557985951_7abf426c1e_z.jpg" /> 
    </div>
</div>
```

Add the following Javascript snippet at the bottom of the page,

```JS
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="homeycombs/js/jquery.homeycombs.js"></script>

<script type="text/javascript">
    $(document).ready(function () {
        $('.honeycombs').honeycombs();
    });
</script>
```

**Credit**
I found the base script and the [demo](http://examples.rabbid.net/honeycombs/demo.html) few years back, recently when i checked the repo and demo were missing. 

Earlier i made some chaneges to the script for one of my projects. Uploading here with with some modification. 


## Contribute

If you want to contribute to this project, feel free to send pull requests. 
