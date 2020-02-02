# gradient
multicolor gradients for all

inspired by [dharma.io](https://dharma.io) and openai, i reverse-engineered how they did multicolor gradients and am sharing them with the world to **spruce up websites**

there are several flavors:

| style        | cdn link           | speed of gradient  | example |
| ------------- |:-------------:| -----:| :------:|
| text fill-in      | https://sdan.cc/assets/css/colorgrad.css | 10s (fast) | https://sdan.io/staticcctexthtml |
| text fill-in | https://sdan.cc/assets/css/colorgrad-slow.css      |    90s (slow) | https://sdan.io/surya (my name) |
| background      | https://sdan.cc/assets/css/colorgrad-slow-background.css      |  60s (medium) | https://sdan.io/staticccbackgroundhtml | 

## what's included in this repo:
### text.html
a simple example of text fill-in (also available here: https://sdan.io/staticcctexthtml). you can play around with it and add your own text/styling
### background.html
a simple example of background takeover (also available here: https://sdan.io/staticccbackgroundhtml). you can play around with it and add your own text/styling

## use it on your website:
depending on if you want text fill-in or a background takeover, add the respective **cdn link, available above, such as: https://sdan.cc/assets/css/colorgrad.css** to your site as such:
```
<link rel="stylesheet" type="text/css" href="https://sdan.cc/assets/css/colorgrad.css">
```
and utilize it for:
### text:
```
<p>
  this text is not colored <span class="colorgrad" display="inline" kind="animated" >this text is colored</span>
</p>
```
### background:
```
<body class="colorgrad">
  <p> the background is so colorful! </p>
</body>
```

## support:
backlinks to `<a href="https://suryad.com">Color brought you by Surya</a>` would be helpful!

feel free to open up issues if there's any problems
