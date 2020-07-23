<link rel="stylesheet" href="./docstyle.css">

<script>
  WebAudioControlsOptions={

  };
</script>

<script src="./webaudio-controls.js"></script>

Basic Usage :
<div style="display:flex;width:100%;flex-wrap:wrap">
<div class="item"><a href="./index.html">Overview</a></div>
<div class="item"><a href="./install.html">Install</a></div>
<div class="item"><a href="./components.html">How it works</a></div>
<div class="item"><a href="./specs.html">Attributes, Functions, Events</a></div>
<div class="item"><a href="./options.html">WebAudioControlsOptions</a></div>
<div class="item"><a href="./knobimage.html">Creating Knob Images</a></div>
<div class="item"><a href="./defstyle.html">Default Style of Controls</a></div>
<div class="item"><a href="./example.html">Examples of Various Attributes</a></div>
</div>
<br/>

Advanced Usage and Application Note :
<div style="display:flex;width:100%;flex-wrap:wrap">
<div class="item"><a href="./knobsamples.html">Knob Samples from KnobGallery</a></div>
<div class="item"><a href="./keyboard.html">Working Keyboard Demo</a></div>
<div class="item"><a href="./knobsize.html">Determining Knob Size</a></div>
<div class="item"><a href="./tracking.html">Slider tracking "rel" and "abs"</a></div>
<div class="item"><a href="./nonlinear.html">Non-Linear Knobs / Sliders</a></div>
<div class="item"><a href="./multifader.html">Multi-Touch Device Support</a></div>
<div class="item"><a href="./midisupport.html">MIDI Support</a></div>
<div class="item cur"><a href="./resizetest.html">Resizing After Creation</a></div>
</div>

---

# Resizing After Creation  

This is a resize test after creating the **webaudio-controls** elements.
Attributes such as "diameter", "width", and "height" can be changed later to resize elements.  
  

---

## Knob
Size :
<button onclick="$('#knob1')[0].diameter=25">Small</button>
<button onclick="$('#knob1')[0].diameter=50">Mid</button>
<button onclick="$('#knob1')[0].diameter=100">Large</button>  
<webaudio-knob id="knob1" diameter="50"></webaudio-knob>
  
<br/>

```html
<button onclick="$('#knob1')[0].diameter=25">Small</button>
<button onclick="$('#knob1')[0].diameter=50">Mid</button>
<button onclick="$('#knob1')[0].diameter=100">Large</button>  
<webaudio-knob id="knob1" diameter="50"></webaudio-knob>
```  
  
<br/>

---

## Param  
Size :
<button onclick="$('#para1')[0].width=25">Width Small</button>
<button onclick="$('#para1')[0].width=100">Width Large</button>
<button onclick="$('#para1')[0].height=16">Height Small</button>
<button onclick="$('#para1')[0].height=48">Height Large</button>
<button onclick="$('#para1')[0].fontsize=9">Font Small</button>
<button onclick="$('#para1')[0].fontsize=48">Font Large</button>  
<webaudio-param id="para1" width="100" height="16"></webaudio-param>  
  
<br/>

```html
<button onclick="$('#para1')[0].width=25">Width Small</button>
<button onclick="$('#para1')[0].width=100">Width Large</button>
<button onclick="$('#para1')[0].height=16">Height Small</button>
<button onclick="$('#para1')[0].height=48">Height Large</button>
<button onclick="$('#para1')[0].fontsize=9">Font Small</button>
<button onclick="$('#para1')[0].fontsize=48">Font Large</button>  
<webaudio-param id="para1" width="100" height="16"></webaudio-param>  
```
  
<br/>

---

## Slider
Size :
<button onclick="$('#sl1')[0].height=50;$('#sl1')[0].width=10">Small</button>
<button onclick="$('#sl1')[0].height=100;$('#sl1')[0].width=20">Mid</button>
<button onclick="$('#sl1')[0].height=200;$('#sl1')[0].width=40">Large</button>  
<webaudio-slider id="sl1" height="100" width="20"></webaudio-slider>  

<br/>

```html
<button onclick="$('#sl1')[0].height=50;$('#sl1')[0].width=10">Small</button>
<button onclick="$('#sl1')[0].height=100;$('#sl1')[0].width=20">Mid</button>
<button onclick="$('#sl1')[0].height=200;$('#sl1')[0].width=40">Large</button>  
<webaudio-slider id="sl1" height="100" width="20"></webaudio-slider>  
```
  
<br/>

---

## Switch
Size :
<button onclick="$('#sw1')[0].height=25;$('#sw1')[0].width=25">Small</button>
<button onclick="$('#sw1')[0].height=50;$('#sw1')[0].width=50">Mid</button>
<button onclick="$('#sw1')[0].height=100;$('#sw1')[0].width=100">Large</button>  
<webaudio-switch id="sw1" height="50" width="50"></webaudio-switch>

<br/>

```html
<button onclick="$('#sw1')[0].height=25;$('#sw1')[0].width=25">Small</button>
<button onclick="$('#sw1')[0].height=50;$('#sw1')[0].width=50">Mid</button>
<button onclick="$('#sw1')[0].height=100;$('#sw1')[0].width=100">Large</button>  
<webaudio-switch id="sw1" height="50" width="50"></webaudio-switch>
```
  
<br/>

---

## Keyboard
Size :
<button onclick="$('#kb1')[0].width=100;$('#kb1')[0].height=20;">Small</button>
<button onclick="$('#kb1')[0].width=200;$('#kb1')[0].height=40;">Mid</button>
<button onclick="$('#kb1')[0].width=400;$('#kb1')[0].height=80;">Large</button>  
Keys :
<button onclick="$('#kb1')[0].keys=13;">13 Keys</button>
<button onclick="$('#kb1')[0].keys=25;">25 Keys</button>
<button onclick="$('#kb1')[0].keys=49;">49 Keys</button>
<button onclick="$('#kb1')[0].keys=61;">61 Keys</button>  
<webaudio-keyboard id="kb1" width="400" height="80"></webaudio-keyboard>
  
<br/>

```html
Size :
<button onclick="$('#kb1')[0].width=100;$('#kb1')[0].height=20;">Small</button>
<button onclick="$('#kb1')[0].width=200;$('#kb1')[0].height=40;">Mid</button>
<button onclick="$('#kb1')[0].width=400;$('#kb1')[0].height=80;">Large</button>  
Keys :
<button onclick="$('#kb1')[0].keys=13;">13 Keys</button>
<button onclick="$('#kb1')[0].keys=25;">25 Keys</button>
<button onclick="$('#kb1')[0].keys=49;">49 Keys</button>
<button onclick="$('#kb1')[0].keys=61;">61 Keys</button>  
<webaudio-keyboard id="kb1" width="400" height="80"></webaudio-keyboard>
```  
  
---