### Text to speech and language translator

<a href="https://www.youtube.com/watch?v=yX2YHVwj8_o"> Watch Demo </a> 



### Content reader
```html
Your Content->  <article> Your Content will be here </article>
Controller ->   <template><span id="control"><b id="tweet"></b><b id="whatsapp"></b><b id="searchit"></b><b id="plays"></b><b id="settings"></b></span></template>
```
Do not change this setting 

### Setting Model
```html
<!-- setting Model-->
<div class="modal fade" id="play-setting" tabindex="-1" role="dialog"
aria-labelledby="play-settingLabel"
aria-hidden="true">
<div class="modal-dialog modal-sm" role="document">
<div class="modal-content col-md-10">
<div class="modal-header">
<h5 class="modal-title" id="play-settingLabel"><img
class="img-logo"
src="./app/src/img/voicelogo.png" alt="">
</div>
<div class="modal-body">
<!-- Setting Panel  -->
<div class="row">
<!--  Volume / -->
<div class="col-md-2"> Volume </div>
<div class="col-md-10"><input type="range" id="volumeSlider"
min="0" max="1" value="0.5"
step="0.1"></div>
<!--  Volume \ -->
</div>
<div class="row">
<!--  Rate / -->
<div class="col-md-2"> Rate </div>
<div class="col-md-10"><input type="range" id="rateSlider"
min="0" max="1" value="0.6"
step="0.1"></div>
<!--  Rate \ -->
</div>
<div class="row">
<!--  Pitch / -->
<div class="col-md-2"> Pitch </div>
<div class="col-md-10"><input type="range" id="pitchSlider"
min="0" max="2" value="0.5"
step="0.1"></div>
<!--  Pitch \ -->
<div class="row justify-content-center">
<!--  Pitch / -->
<div class="input-group col-md-11">
<div class="input-group-prepend">
<span class="input-group-text" id="basic-addon1">Voice</span>
</div>
<select class="form-control" id="voiceOptions"></select>
</div>
<div class="input-group col-md-11 mt-2">
<div class="input-group-prepend">
<span class="input-group-text" id="basic-addon1">Languages</span>
</div>
<div class="form-control" id="google_translate_element"></div>
</div>
<!--  Pitch \ -->
</div></div><div class="modal-footer justify-content-center">
<div class="btn-group">
<button type="button" class="btn btn-dark ripple-effect"
data-dismiss="modal">Save
Changes</button>
</div></div></div>
<div>
<div></div>
<!-- setting -->
```
Copy and paste setting modal in the body area

Stylesheet and javascript file
### Importants files
```html
Top -> Powerful-Text-to-Speech\app\src\css\text-to-speech.css
Buttom-> Powerful-Text-to-Speech\app\src\js\contentscript.js
```


## Contributors
Thank you to all our backers!  [[Become a backer](https://opencollective.com/Bootstrap-extra#backer)]
[![Backers](https://opencollective.com/Bootstrap-extra/backers.svg?width=890)](https://opencollective.com/Bootstrap-extra#backers)


<a href="CODE_CONTRIBUTORS.md"><img src="https://opencollective.com/swiper/contributors.svg?width=890&button=false" /></a>

![Slack](https://img.shields.io/badge/MIT-License-green) ![Slack](https://img.shields.io/badge/plugin-0-blue) ![Slack](https://img.shields.io/badge/rating%20count-9.1kb%20total-yellowgreen) 
![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg)
