# images_colab

this site contains some images






<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />

<title>Metod_beskrivning</title>

<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>



<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.7.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.7.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.7.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff2?v=4.7.0') format('woff2'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.7.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.7.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.7.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.fa-pull-left {
  float: left;
}
.fa-pull-right {
  float: right;
}
.fa.fa-pull-left {
  margin-right: .3em;
}
.fa.fa-pull-right {
  margin-left: .3em;
}
/* Deprecated as of 4.4.0 */
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8);
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=1)";
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2)";
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=3)";
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)";
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)";
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook-f:before,
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-feed:before,
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before,
.fa-gratipay:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper-pp:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-resistance:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-y-combinator-square:before,
.fa-yc-square:before,
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
.fa-buysellads:before {
  content: "\f20d";
}
.fa-connectdevelop:before {
  content: "\f20e";
}
.fa-dashcube:before {
  content: "\f210";
}
.fa-forumbee:before {
  content: "\f211";
}
.fa-leanpub:before {
  content: "\f212";
}
.fa-sellsy:before {
  content: "\f213";
}
.fa-shirtsinbulk:before {
  content: "\f214";
}
.fa-simplybuilt:before {
  content: "\f215";
}
.fa-skyatlas:before {
  content: "\f216";
}
.fa-cart-plus:before {
  content: "\f217";
}
.fa-cart-arrow-down:before {
  content: "\f218";
}
.fa-diamond:before {
  content: "\f219";
}
.fa-ship:before {
  content: "\f21a";
}
.fa-user-secret:before {
  content: "\f21b";
}
.fa-motorcycle:before {
  content: "\f21c";
}
.fa-street-view:before {
  content: "\f21d";
}
.fa-heartbeat:before {
  content: "\f21e";
}
.fa-venus:before {
  content: "\f221";
}
.fa-mars:before {
  content: "\f222";
}
.fa-mercury:before {
  content: "\f223";
}
.fa-intersex:before,
.fa-transgender:before {
  content: "\f224";
}
.fa-transgender-alt:before {
  content: "\f225";
}
.fa-venus-double:before {
  content: "\f226";
}
.fa-mars-double:before {
  content: "\f227";
}
.fa-venus-mars:before {
  content: "\f228";
}
.fa-mars-stroke:before {
  content: "\f229";
}
.fa-mars-stroke-v:before {
  content: "\f22a";
}
.fa-mars-stroke-h:before {
  content: "\f22b";
}
.fa-neuter:before {
  content: "\f22c";
}
.fa-genderless:before {
  content: "\f22d";
}
.fa-facebook-official:before {
  content: "\f230";
}
.fa-pinterest-p:before {
  content: "\f231";
}
.fa-whatsapp:before {
  content: "\f232";
}
.fa-server:before {
  content: "\f233";
}
.fa-user-plus:before {
  content: "\f234";
}
.fa-user-times:before {
  content: "\f235";
}
.fa-hotel:before,
.fa-bed:before {
  content: "\f236";
}
.fa-viacoin:before {
  content: "\f237";
}
.fa-train:before {
  content: "\f238";
}
.fa-subway:before {
  content: "\f239";
}
.fa-medium:before {
  content: "\f23a";
}
.fa-yc:before,
.fa-y-combinator:before {
  content: "\f23b";
}
.fa-optin-monster:before {
  content: "\f23c";
}
.fa-opencart:before {
  content: "\f23d";
}
.fa-expeditedssl:before {
  content: "\f23e";
}
.fa-battery-4:before,
.fa-battery:before,
.fa-battery-full:before {
  content: "\f240";
}
.fa-battery-3:before,
.fa-battery-three-quarters:before {
  content: "\f241";
}
.fa-battery-2:before,
.fa-battery-half:before {
  content: "\f242";
}
.fa-battery-1:before,
.fa-battery-quarter:before {
  content: "\f243";
}
.fa-battery-0:before,
.fa-battery-empty:before {
  content: "\f244";
}
.fa-mouse-pointer:before {
  content: "\f245";
}
.fa-i-cursor:before {
  content: "\f246";
}
.fa-object-group:before {
  content: "\f247";
}
.fa-object-ungroup:before {
  content: "\f248";
}
.fa-sticky-note:before {
  content: "\f249";
}
.fa-sticky-note-o:before {
  content: "\f24a";
}
.fa-cc-jcb:before {
  content: "\f24b";
}
.fa-cc-diners-club:before {
  content: "\f24c";
}
.fa-clone:before {
  content: "\f24d";
}
.fa-balance-scale:before {
  content: "\f24e";
}
.fa-hourglass-o:before {
  content: "\f250";
}
.fa-hourglass-1:before,
.fa-hourglass-start:before {
  content: "\f251";
}
.fa-hourglass-2:before,
.fa-hourglass-half:before {
  content: "\f252";
}
.fa-hourglass-3:before,
.fa-hourglass-end:before {
  content: "\f253";
}
.fa-hourglass:before {
  content: "\f254";
}
.fa-hand-grab-o:before,
.fa-hand-rock-o:before {
  content: "\f255";
}
.fa-hand-stop-o:before,
.fa-hand-paper-o:before {
  content: "\f256";
}
.fa-hand-scissors-o:before {
  content: "\f257";
}
.fa-hand-lizard-o:before {
  content: "\f258";
}
.fa-hand-spock-o:before {
  content: "\f259";
}
.fa-hand-pointer-o:before {
  content: "\f25a";
}
.fa-hand-peace-o:before {
  content: "\f25b";
}
.fa-trademark:before {
  content: "\f25c";
}
.fa-registered:before {
  content: "\f25d";
}
.fa-creative-commons:before {
  content: "\f25e";
}
.fa-gg:before {
  content: "\f260";
}
.fa-gg-circle:before {
  content: "\f261";
}
.fa-tripadvisor:before {
  content: "\f262";
}
.fa-odnoklassniki:before {
  content: "\f263";
}
.fa-odnoklassniki-square:before {
  content: "\f264";
}
.fa-get-pocket:before {
  content: "\f265";
}
.fa-wikipedia-w:before {
  content: "\f266";
}
.fa-safari:before {
  content: "\f267";
}
.fa-chrome:before {
  content: "\f268";
}
.fa-firefox:before {
  content: "\f269";
}
.fa-opera:before {
  content: "\f26a";
}
.fa-internet-explorer:before {
  content: "\f26b";
}
.fa-tv:before,
.fa-television:before {
  content: "\f26c";
}
.fa-contao:before {
  content: "\f26d";
}
.fa-500px:before {
  content: "\f26e";
}
.fa-amazon:before {
  content: "\f270";
}
.fa-calendar-plus-o:before {
  content: "\f271";
}
.fa-calendar-minus-o:before {
  content: "\f272";
}
.fa-calendar-times-o:before {
  content: "\f273";
}
.fa-calendar-check-o:before {
  content: "\f274";
}
.fa-industry:before {
  content: "\f275";
}
.fa-map-pin:before {
  content: "\f276";
}
.fa-map-signs:before {
  content: "\f277";
}
.fa-map-o:before {
  content: "\f278";
}
.fa-map:before {
  content: "\f279";
}
.fa-commenting:before {
  content: "\f27a";
}
.fa-commenting-o:before {
  content: "\f27b";
}
.fa-houzz:before {
  content: "\f27c";
}
.fa-vimeo:before {
  content: "\f27d";
}
.fa-black-tie:before {
  content: "\f27e";
}
.fa-fonticons:before {
  content: "\f280";
}
.fa-reddit-alien:before {
  content: "\f281";
}
.fa-edge:before {
  content: "\f282";
}
.fa-credit-card-alt:before {
  content: "\f283";
}
.fa-codiepie:before {
  content: "\f284";
}
.fa-modx:before {
  content: "\f285";
}
.fa-fort-awesome:before {
  content: "\f286";
}
.fa-usb:before {
  content: "\f287";
}
.fa-product-hunt:before {
  content: "\f288";
}
.fa-mixcloud:before {
  content: "\f289";
}
.fa-scribd:before {
  content: "\f28a";
}
.fa-pause-circle:before {
  content: "\f28b";
}
.fa-pause-circle-o:before {
  content: "\f28c";
}
.fa-stop-circle:before {
  content: "\f28d";
}
.fa-stop-circle-o:before {
  content: "\f28e";
}
.fa-shopping-bag:before {
  content: "\f290";
}
.fa-shopping-basket:before {
  content: "\f291";
}
.fa-hashtag:before {
  content: "\f292";
}
.fa-bluetooth:before {
  content: "\f293";
}
.fa-bluetooth-b:before {
  content: "\f294";
}
.fa-percent:before {
  content: "\f295";
}
.fa-gitlab:before {
  content: "\f296";
}
.fa-wpbeginner:before {
  content: "\f297";
}
.fa-wpforms:before {
  content: "\f298";
}
.fa-envira:before {
  content: "\f299";
}
.fa-universal-access:before {
  content: "\f29a";
}
.fa-wheelchair-alt:before {
  content: "\f29b";
}
.fa-question-circle-o:before {
  content: "\f29c";
}
.fa-blind:before {
  content: "\f29d";
}
.fa-audio-description:before {
  content: "\f29e";
}
.fa-volume-control-phone:before {
  content: "\f2a0";
}
.fa-braille:before {
  content: "\f2a1";
}
.fa-assistive-listening-systems:before {
  content: "\f2a2";
}
.fa-asl-interpreting:before,
.fa-american-sign-language-interpreting:before {
  content: "\f2a3";
}
.fa-deafness:before,
.fa-hard-of-hearing:before,
.fa-deaf:before {
  content: "\f2a4";
}
.fa-glide:before {
  content: "\f2a5";
}
.fa-glide-g:before {
  content: "\f2a6";
}
.fa-signing:before,
.fa-sign-language:before {
  content: "\f2a7";
}
.fa-low-vision:before {
  content: "\f2a8";
}
.fa-viadeo:before {
  content: "\f2a9";
}
.fa-viadeo-square:before {
  content: "\f2aa";
}
.fa-snapchat:before {
  content: "\f2ab";
}
.fa-snapchat-ghost:before {
  content: "\f2ac";
}
.fa-snapchat-square:before {
  content: "\f2ad";
}
.fa-pied-piper:before {
  content: "\f2ae";
}
.fa-first-order:before {
  content: "\f2b0";
}
.fa-yoast:before {
  content: "\f2b1";
}
.fa-themeisle:before {
  content: "\f2b2";
}
.fa-google-plus-circle:before,
.fa-google-plus-official:before {
  content: "\f2b3";
}
.fa-fa:before,
.fa-font-awesome:before {
  content: "\f2b4";
}
.fa-handshake-o:before {
  content: "\f2b5";
}
.fa-envelope-open:before {
  content: "\f2b6";
}
.fa-envelope-open-o:before {
  content: "\f2b7";
}
.fa-linode:before {
  content: "\f2b8";
}
.fa-address-book:before {
  content: "\f2b9";
}
.fa-address-book-o:before {
  content: "\f2ba";
}
.fa-vcard:before,
.fa-address-card:before {
  content: "\f2bb";
}
.fa-vcard-o:before,
.fa-address-card-o:before {
  content: "\f2bc";
}
.fa-user-circle:before {
  content: "\f2bd";
}
.fa-user-circle-o:before {
  content: "\f2be";
}
.fa-user-o:before {
  content: "\f2c0";
}
.fa-id-badge:before {
  content: "\f2c1";
}
.fa-drivers-license:before,
.fa-id-card:before {
  content: "\f2c2";
}
.fa-drivers-license-o:before,
.fa-id-card-o:before {
  content: "\f2c3";
}
.fa-quora:before {
  content: "\f2c4";
}
.fa-free-code-camp:before {
  content: "\f2c5";
}
.fa-telegram:before {
  content: "\f2c6";
}
.fa-thermometer-4:before,
.fa-thermometer:before,
.fa-thermometer-full:before {
  content: "\f2c7";
}
.fa-thermometer-3:before,
.fa-thermometer-three-quarters:before {
  content: "\f2c8";
}
.fa-thermometer-2:before,
.fa-thermometer-half:before {
  content: "\f2c9";
}
.fa-thermometer-1:before,
.fa-thermometer-quarter:before {
  content: "\f2ca";
}
.fa-thermometer-0:before,
.fa-thermometer-empty:before {
  content: "\f2cb";
}
.fa-shower:before {
  content: "\f2cc";
}
.fa-bathtub:before,
.fa-s15:before,
.fa-bath:before {
  content: "\f2cd";
}
.fa-podcast:before {
  content: "\f2ce";
}
.fa-window-maximize:before {
  content: "\f2d0";
}
.fa-window-minimize:before {
  content: "\f2d1";
}
.fa-window-restore:before {
  content: "\f2d2";
}
.fa-times-rectangle:before,
.fa-window-close:before {
  content: "\f2d3";
}
.fa-times-rectangle-o:before,
.fa-window-close-o:before {
  content: "\f2d4";
}
.fa-bandcamp:before {
  content: "\f2d5";
}
.fa-grav:before {
  content: "\f2d6";
}
.fa-etsy:before {
  content: "\f2d7";
}
.fa-imdb:before {
  content: "\f2d8";
}
.fa-ravelry:before {
  content: "\f2d9";
}
.fa-eercast:before {
  content: "\f2da";
}
.fa-microchip:before {
  content: "\f2db";
}
.fa-snowflake-o:before {
  content: "\f2dc";
}
.fa-superpowers:before {
  content: "\f2dd";
}
.fa-wpexplorer:before {
  content: "\f2de";
}
.fa-meetup:before {
  content: "\f2e0";
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
div.traceback-wrapper pre.traceback {
  max-height: 600px;
  overflow: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 5px;
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
[dir="rtl"] #ipython_notebook {
  margin-right: 10px;
  margin-left: 0;
}
[dir="rtl"] #ipython_notebook.pull-left {
  float: right !important;
  float: right;
}
.flex-spacer {
  flex: 1;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#kernel_logo_widget {
  margin: 0 10px;
}
span#login_widget {
  float: right;
}
[dir="rtl"] span#login_widget {
  float: left;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
.modal-header {
  cursor: move;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
[dir="rtl"] .center-nav form.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] .center-nav .navbar-text {
  float: right;
}
[dir="rtl"] .navbar-inner {
  text-align: right;
}
[dir="rtl"] div.text-left {
  text-align: right;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  position: absolute;
  display: block;
  width: 100%;
  height: 100%;
  overflow: hidden;
  cursor: pointer;
  opacity: 0;
  z-index: 2;
}
.alternate_upload .btn-xs > input.fileinput {
  margin: -1px -5px;
}
.alternate_upload .btn-upload {
  position: relative;
  height: 22px;
}
::-webkit-file-upload-button {
  cursor: pointer;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
ul#tabs {
  margin-bottom: 4px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
[dir="rtl"] ul#tabs.nav-tabs > li {
  float: right;
}
[dir="rtl"] ul#tabs.nav.nav-tabs {
  padding-right: 0;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons .pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .list_toolbar .col-sm-4,
[dir="rtl"] .list_toolbar .col-sm-8 {
  float: right;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: text-bottom;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
[dir="rtl"] .list_item > div input {
  margin-right: 0;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_modified {
  margin-right: 7px;
  margin-left: 7px;
}
[dir="rtl"] .item_modified.pull-right {
  float: left !important;
  float: left;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
[dir="rtl"] .item_buttons.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .item_buttons .kernel-name {
  margin-left: 7px;
  float: right;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
.sort_button {
  display: inline-block;
  padding-left: 7px;
}
[dir="rtl"] .sort_button.pull-right {
  float: left !important;
  float: left;
}
#tree-selector {
  padding-right: 0px;
}
#button-select-all {
  min-width: 50px;
}
[dir="rtl"] #button-select-all.btn {
  float: right ;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
  margin-top: 2px;
  height: 16px;
}
[dir="rtl"] #select-all.pull-left {
  float: right !important;
  float: right;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.fa-pull-left {
  margin-right: .3em;
}
.folder_icon:before.fa-pull-right {
  margin-left: .3em;
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.fa-pull-left {
  margin-right: .3em;
}
.file_icon:before.fa-pull-right {
  margin-left: .3em;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
#new-menu .dropdown-header {
  font-size: 10px;
  border-bottom: 1px solid #e5e5e5;
  padding: 0 0 3px;
  margin: -3px 20px 0;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.move-button {
  display: none;
}
.download-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
.CodeMirror-dialog {
  background-color: #fff;
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI escape sequences */
/* The color values are a mix of
   http://www.xcolors.net/dl/baskerville-ivorylight and
   http://www.xcolors.net/dl/euphrasia */
.ansi-black-fg {
  color: #3E424D;
}
.ansi-black-bg {
  background-color: #3E424D;
}
.ansi-black-intense-fg {
  color: #282C36;
}
.ansi-black-intense-bg {
  background-color: #282C36;
}
.ansi-red-fg {
  color: #E75C58;
}
.ansi-red-bg {
  background-color: #E75C58;
}
.ansi-red-intense-fg {
  color: #B22B31;
}
.ansi-red-intense-bg {
  background-color: #B22B31;
}
.ansi-green-fg {
  color: #00A250;
}
.ansi-green-bg {
  background-color: #00A250;
}
.ansi-green-intense-fg {
  color: #007427;
}
.ansi-green-intense-bg {
  background-color: #007427;
}
.ansi-yellow-fg {
  color: #DDB62B;
}
.ansi-yellow-bg {
  background-color: #DDB62B;
}
.ansi-yellow-intense-fg {
  color: #B27D12;
}
.ansi-yellow-intense-bg {
  background-color: #B27D12;
}
.ansi-blue-fg {
  color: #208FFB;
}
.ansi-blue-bg {
  background-color: #208FFB;
}
.ansi-blue-intense-fg {
  color: #0065CA;
}
.ansi-blue-intense-bg {
  background-color: #0065CA;
}
.ansi-magenta-fg {
  color: #D160C4;
}
.ansi-magenta-bg {
  background-color: #D160C4;
}
.ansi-magenta-intense-fg {
  color: #A03196;
}
.ansi-magenta-intense-bg {
  background-color: #A03196;
}
.ansi-cyan-fg {
  color: #60C6C8;
}
.ansi-cyan-bg {
  background-color: #60C6C8;
}
.ansi-cyan-intense-fg {
  color: #258F8F;
}
.ansi-cyan-intense-bg {
  background-color: #258F8F;
}
.ansi-white-fg {
  color: #C5C1B4;
}
.ansi-white-bg {
  background-color: #C5C1B4;
}
.ansi-white-intense-fg {
  color: #A1A6B2;
}
.ansi-white-intense-bg {
  background-color: #A1A6B2;
}
.ansi-default-inverse-fg {
  color: #FFFFFF;
}
.ansi-default-inverse-bg {
  background-color: #000000;
}
.ansi-bold {
  font-weight: bold;
}
.ansi-underline {
  text-decoration: underline;
}
/* The following styles are deprecated an will be removed in a future version */
.ansibold {
  font-weight: bold;
}
.ansi-inverse {
  outline: 0.5px dotted;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  position: relative;
  overflow: visible;
}
div.cell:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: transparent;
}
div.cell.jupyter-soft-selected {
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected,
div.cell.selected.jupyter-soft-selected {
  border-color: #ababab;
}
div.cell.selected:before,
div.cell.selected.jupyter-soft-selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #42A5F5;
}
@media print {
  div.cell.selected,
  div.cell.selected.jupyter-soft-selected {
    border-color: transparent;
  }
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
}
.edit_mode div.cell.selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #66BB6A;
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  /* Note that this should set vertical padding only, since CodeMirror assumes
       that horizontal padding will be set on CodeMirror pre */
  padding: 0.4em 0;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. This sets horizontal padding only,
    use .CodeMirror-lines for vertical */
  padding: 0 0.4em;
  border: 0;
  border-radius: 0;
}
.CodeMirror-cursor {
  border-left: 1.4px solid black;
}
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .CodeMirror-cursor {
    border-left: 2px solid black;
  }
}
@media screen and (min-width: 4320px) {
  .CodeMirror-cursor {
    border-left: 4px solid black;
  }
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
div.output_area .mglyph > img {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 1px 0 1px 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul:not(.list-inline),
.rendered_html ol:not(.list-inline) {
  padding-left: 2em;
}
.rendered_html ul {
  list-style: disc;
}
.rendered_html ul ul {
  list-style: square;
  margin-top: 0;
}
.rendered_html ul ul ul {
  list-style: circle;
}
.rendered_html ol {
  list-style: decimal;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin-top: 0;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
  padding: 0px;
  background-color: #fff;
}
.rendered_html code {
  background-color: #eff0f1;
}
.rendered_html p code {
  padding: 1px 5px;
}
.rendered_html pre code {
  background-color: #fff;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  color: #000;
  font-size: 100%;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: none;
  border-collapse: collapse;
  border-spacing: 0;
  color: black;
  font-size: 12px;
  table-layout: fixed;
}
.rendered_html thead {
  border-bottom: 1px solid black;
  vertical-align: bottom;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  text-align: right;
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html tbody tr:nth-child(odd) {
  background: #f5f5f5;
}
.rendered_html tbody tr:hover {
  background: rgba(66, 165, 245, 0.2);
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
.rendered_html .alert {
  margin-bottom: initial;
}
.rendered_html * + .alert {
  margin-top: 1em;
}
[dir="rtl"] .rendered_html p {
  text-align: right;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.rendered .rendered_html tr,
.text_cell.rendered .rendered_html th,
.text_cell.rendered .rendered_html td {
  max-width: none;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.text_cell .dropzone .input_area {
  border: 2px dashed #bababa;
  margin: -1px;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
.jupyter-keybindings {
  padding: 1px;
  line-height: 24px;
  border-bottom: 1px solid gray;
}
.jupyter-keybindings input {
  margin: 0;
  padding: 0;
  border: none;
}
.jupyter-keybindings i {
  padding: 6px;
}
.well code {
  background-color: #ffffff;
  border-color: #ababab;
  border-width: 1px;
  border-style: solid;
  padding: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.tags_button_container {
  width: 100%;
  display: flex;
}
.tag-container {
  display: flex;
  flex-direction: row;
  flex-grow: 1;
  overflow: hidden;
  position: relative;
}
.tag-container > * {
  margin: 0 4px;
}
.remove-tag-btn {
  margin-left: 4px;
}
.tags-input {
  display: flex;
}
.cell-tag:last-child:after {
  content: "";
  position: absolute;
  right: 0;
  width: 40px;
  height: 100%;
  /* Fade to background color of cell toolbar */
  background: linear-gradient(to right, rgba(0, 0, 0, 0), #EEE);
}
.tags-input > * {
  margin-left: 4px;
}
.cell-tag,
.tags-input input,
.tags-input button {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  box-shadow: none;
  width: inherit;
  font-size: inherit;
  height: 22px;
  line-height: 22px;
  padding: 0px 4px;
  display: inline-block;
}
.cell-tag:focus,
.tags-input input:focus,
.tags-input button:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.cell-tag::-moz-placeholder,
.tags-input input::-moz-placeholder,
.tags-input button::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.cell-tag:-ms-input-placeholder,
.tags-input input:-ms-input-placeholder,
.tags-input button:-ms-input-placeholder {
  color: #999;
}
.cell-tag::-webkit-input-placeholder,
.tags-input input::-webkit-input-placeholder,
.tags-input button::-webkit-input-placeholder {
  color: #999;
}
.cell-tag::-ms-expand,
.tags-input input::-ms-expand,
.tags-input button::-ms-expand {
  border: 0;
  background-color: transparent;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
.cell-tag[readonly],
.tags-input input[readonly],
.tags-input button[readonly],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  background-color: #eeeeee;
  opacity: 1;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  cursor: not-allowed;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button {
  height: auto;
}
select.cell-tag,
select.tags-input input,
select.tags-input button {
  height: 30px;
  line-height: 30px;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button,
select[multiple].cell-tag,
select[multiple].tags-input input,
select[multiple].tags-input button {
  height: auto;
}
.cell-tag,
.tags-input button {
  padding: 0px 4px;
}
.cell-tag {
  background-color: #fff;
  white-space: nowrap;
}
.tags-input input[type=text]:focus {
  outline: none;
  box-shadow: none;
  border-color: #ccc;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
[dir="rtl"] #kernel_logo_widget {
  float: left !important;
  float: left;
}
.modal .modal-body .move-path {
  display: flex;
  flex-direction: row;
  justify-content: space;
  align-items: center;
}
.modal .modal-body .move-path .server-root {
  padding-right: 20px;
}
.modal .modal-body .move-path .path-input {
  flex: 1;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
[dir="rtl"] #menubar .navbar-toggle {
  float: right;
}
[dir="rtl"] #menubar .navbar-collapse {
  clear: right;
}
[dir="rtl"] #menubar .navbar-nav {
  float: right;
}
[dir="rtl"] #menubar .nav {
  padding-right: 0px;
}
[dir="rtl"] #menubar .navbar-nav > li {
  float: right;
}
[dir="rtl"] #menubar .navbar-right {
  float: left !important;
}
[dir="rtl"] ul.dropdown-menu {
  text-align: right;
  left: auto;
}
[dir="rtl"] ul#new-menu.dropdown-menu {
  right: auto;
  left: 0;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
[dir="rtl"] i.menu-icon.pull-right {
  float: left !important;
  float: left;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
[dir="rtl"] ul#help_menu li a {
  padding-left: 2.2em;
}
[dir="rtl"] ul#help_menu li a i {
  margin-right: 0;
  margin-left: -1.2em;
}
[dir="rtl"] ul#help_menu li a i.pull-right {
  float: left !important;
  float: left;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
[dir="rtl"] .dropdown-submenu > .dropdown-menu {
  right: 100%;
  margin-right: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.fa-pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.fa-pull-right {
  margin-left: .3em;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
[dir="rtl"] .dropdown-submenu > a:after {
  float: left;
  content: "\f0d9";
  margin-right: 0;
  margin-left: -10px;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
[dir="rtl"] #notification_area {
  float: left !important;
  float: left;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] .indicator_area {
  float: left !important;
  float: left;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
[dir="rtl"] #kernel_indicator {
  float: left !important;
  float: left;
  border-left: 0;
  border-right: 1px solid;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] #modal_indicator {
  float: left !important;
  float: left;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  height: 30px;
  margin-top: 4px;
  display: flex;
  justify-content: flex-start;
  align-items: baseline;
  width: 50%;
  flex: 1;
}
span.save_widget span.filename {
  height: 100%;
  line-height: 1em;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
[dir="rtl"] span.save_widget.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] span.save_widget span.filename {
  margin-left: 0;
  margin-right: 16px;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
  white-space: nowrap;
  padding: 0 5px;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
    padding: 0 0 0 5px;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
.toolbar-btn-label {
  margin-left: 6px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
[dir="rtl"] .btn-group > .btn,
.btn-group-vertical > .btn {
  float: right;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
[dir="rtl"] ul.typeahead-list i {
  margin-left: 0;
  margin-right: -10px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
ul.typeahead-list  > li > a.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .typeahead-list {
  text-align: right;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  min-width: 20px;
  color: transparent;
}
[dir="rtl"] .no-shortcut.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .command-shortcut.pull-right {
  float: left !important;
  float: left;
}
.command-shortcut:before {
  content: "(command mode)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
[dir="rtl"] .edit-shortcut.pull-right {
  float: left !important;
  float: left;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
[dir="ltr"] #find-and-replace .input-group-btn + .form-control {
  border-left: none;
}
[dir="rtl"] #find-and-replace .input-group-btn + .form-control {
  border-right: none;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>
<style type="text/css">
    
/* Temporary definitions which will become obsolete with Notebook release 5.0 */
.ansi-black-fg { color: #3E424D; }
.ansi-black-bg { background-color: #3E424D; }
.ansi-black-intense-fg { color: #282C36; }
.ansi-black-intense-bg { background-color: #282C36; }
.ansi-red-fg { color: #E75C58; }
.ansi-red-bg { background-color: #E75C58; }
.ansi-red-intense-fg { color: #B22B31; }
.ansi-red-intense-bg { background-color: #B22B31; }
.ansi-green-fg { color: #00A250; }
.ansi-green-bg { background-color: #00A250; }
.ansi-green-intense-fg { color: #007427; }
.ansi-green-intense-bg { background-color: #007427; }
.ansi-yellow-fg { color: #DDB62B; }
.ansi-yellow-bg { background-color: #DDB62B; }
.ansi-yellow-intense-fg { color: #B27D12; }
.ansi-yellow-intense-bg { background-color: #B27D12; }
.ansi-blue-fg { color: #208FFB; }
.ansi-blue-bg { background-color: #208FFB; }
.ansi-blue-intense-fg { color: #0065CA; }
.ansi-blue-intense-bg { background-color: #0065CA; }
.ansi-magenta-fg { color: #D160C4; }
.ansi-magenta-bg { background-color: #D160C4; }
.ansi-magenta-intense-fg { color: #A03196; }
.ansi-magenta-intense-bg { background-color: #A03196; }
.ansi-cyan-fg { color: #60C6C8; }
.ansi-cyan-bg { background-color: #60C6C8; }
.ansi-cyan-intense-fg { color: #258F8F; }
.ansi-cyan-intense-bg { background-color: #258F8F; }
.ansi-white-fg { color: #C5C1B4; }
.ansi-white-bg { background-color: #C5C1B4; }
.ansi-white-intense-fg { color: #A1A6B2; }
.ansi-white-intense-bg { background-color: #A1A6B2; }

.ansi-bold { font-weight: bold; }

    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/latest.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Metod-beskrivning">Metod beskrivning<a class="anchor-link" href="#Metod-beskrivning">&#182;</a></h1><p>Syfte med metod är komma fram till priser av ingående enskilda element genom att studera ingående mängder element i en portfölj.
Med denna metod kan man helt matematiskt korrekt bryta ner ett klump pris och sen använda dessa nedbrytade delar för att prognosera/förutsäga totalpris till andra projekt/portfoljer.<a href="https://">länktext</a></p>
<p>Offerter i portföljen kan anses som <em>ett system av linjära ekvationer</em> där ingående material kan betraktas som komponentmängder (mängder måste då vara kända eller antagdna vid upphandlingen): $A_1, A_2, A_3 ...A_n$ och deras motsvarande priser (som är från början okända): $x_1,  x_2 , x_3 ...x_n$  där totalpriset (det enda pris som är angivet från början i offert) $P$ är resultatet.</p>
<p>För att komma fram till underligande komoponent priser $x_1,  x_2 , x_3$ måste eqvationer sammanfattas i ett system av linjära ekvationer</p>
$$A_1x_1 + A_2x_2 + A_3x_3 = P_1$$$$A_1x_1 + A_2x_2 + A_3x_3 = P_2$$$$A_1x_1 + A_2x_2 + A_3x_3 = P_3$$<p>dessa kan sen beskrivas i följande ekvation:</p>
<h1 id="$$Ax=P$$">$$Ax=P$$<a class="anchor-link" href="#$$Ax=P$$">&#182;</a></h1><p>där $Ax$ och $P$ sammanfattas i matris form enligt följande:</p>
$$ Ax = \begin{bmatrix} A_1{⋅}x_1 &amp; A_2{⋅}x_2 &amp;  A_3{⋅}x_3 &amp;\cdots \\ A_1{⋅}x_1 &amp; A_2{⋅}x_2 &amp; A_3{⋅}x_3 &amp;\cdots\\ A_1{⋅}x_1 &amp; A_2{⋅}x_2 &amp; A_3{⋅}x_3 &amp;\cdots\\\vdots &amp; \vdots &amp; \vdots \\
\end{bmatrix} \text{och}\  P = \begin{bmatrix} P_1 \\P_2 \\ P_3\\\ \vdots \\
\end{bmatrix}$$<p></p>
<p>${Ax}$ kan sen delas vidare i två vektorer motsvarande:</p>
$$ A = \begin{bmatrix} A_1 &amp; A_2 &amp;  A_3 \\ A_1 &amp; A_2 &amp; A_3 \\ A_1 &amp; A_2 &amp; A_3 \end{bmatrix}$$<p></p>
<p>\</p>
$$ x = \begin{bmatrix} x_1 \\  x_2  \\ x_3 \end{bmatrix}$$<p>Enligt matriser ovan, kan $x_1,  x_2 , x_3$ bestämmas genom att lösa ekvations system</p>
$$ x_1 \begin{bmatrix} A_1 \\ A_2 \\  A_3 \end{bmatrix} + x_2 \begin{bmatrix} A_1 \\ A_2 \\  A_3 \end{bmatrix} + x_3 \begin{bmatrix} A_1 \\ A_2 \\  A_3 \end{bmatrix} = \begin{bmatrix} P_1 \\P_2 \\ P_3 \\
\end{bmatrix}$$<p>\</p>
<p>Genoma att lösa $Ax=P$ kommer man då till komoponent priser $x_1,  x_2 , x_3$ i portföljen:</p>
<p>\
$$x_1 = \text{elementpris}_1 $$</p>
$$x_2 = \text{elementpris}_2$$$$x_3 = \text{elementpris}_3$$
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Exempel-1">Exempel 1<a class="anchor-link" href="#Exempel-1">&#182;</a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Offert som visar produkt bestående av 3 olika ingående delar och som visar enbart totalpriset per produkt (priser av ingpende delar framgår inte)</p>
<hr>
<p><img src="data:image/png;base64,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" alt="image.png"></p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Genoma att lösa $Ax=P$ kommer man då till följande komoponent priser som sen omvandlade till totalpriset visar skillnad mot det offererade priset</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><img src="data:image/png;base64,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" alt="image.png"></p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Exempel-2">Exempel 2<a class="anchor-link" href="#Exempel-2">&#182;</a></h1><p>obs: detta är ett exempel med väldigt grova ingångsvärden, som ger större spridning i resultatet</p>
<p>Entreprenadpris av några betong sändwich projekt, där vid lösning av $Ax=P$ två nedersta, rödmarkerade priser var inte med i beräkningen och då beräknade kalkylpriser är framtagna matematiskt utan att ha med ingångsvärden i beräkningsmodell - alltså rent prognospris, som ändå kommer nära med tanke på litet antal ingångsvärden.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAskAAABoCAYAAAAD6m2PAAAgAElEQVR4nO2dsZaqOhfH/3zrPopOMccngCfA00xlOx2W2kxnaTcNlNpNazXNwSfQJ2BZDLxLvgLQEJKQICo4+7fWXXeOCcnO3js7AULiJEnCQBAEQRAEQRDEmf8A4M+fP4+Wg+gBjuMAABij+6Yh4zgO2fDJIRsPG4q1BA/5Q/8obfK/B8tBEARBEARBEL2DJskEQRAEQRAEIVCdJGcRPMeBI/1vjv2DhHwMe8wdD1FmeVkWwbuBrvbzwg5ehIj721Y8K1RtKfxk/rscQs6N7N0ZZEM1QrwbrC7Ixmr2c24MaxHP7wWNvRz3HnszRF6LflKp77oytOzn1/luh3J26ocNZWaRJ4/Ndx5zJU+SA8SMgdX+28BvKq3vE4Z7MFrgYKIrK/b43roIUwZ2eMHp/PcCI9MiurJNFsEb7zBLGTbdNrI/GOtqj/l4ieMdROoUsiFK203iIr7FAbbTHk+ibCEb5+nTJI+VjIHFEyzHfR6faOy9ipuMvY8mQ7TeIggmWH62tG5f9aKVa4/PJfK+GwfYri8PBPefS0zi+7WHllsMgewHCSZ4GQl/35095uMdZukBi4fU3x/yu9wpkiCA+2hhrCAbAgD239i6IT7KSOt/IHSPOKUPlaojyMYAikGY04H/hgAJfp7lRoh4frJ/2B0DvH28wt1+/56bIH6eM36FezwhBYAswjrh4vYdsJ8kF3esEfco3IsyXJ6qbTEtXw1kETxvjrnHvzLaYy59jZQh8jxEEfd6rHzGblOOUr6Cyus3rg4xbf7NN9pcNvGO3uZ1X+WVG6fDs14dONzfuQgaPZzl4q9r+7Rsj7kzBWLJwCuT+6w3B/OIS5/vq/nP+tfoWFdHk72t/UTixzJeVkgZw+HjtY0yHwTZ8Iy/Ed7EpDgN7pWADLKxiixaY+vO8HeoNw409t5u7OUprjvLrpPboIz9vH5NFnlG5WT/djgGb/BHC6yCLdalTLU3B3kfrtu17NeKtwxiW5U+Ir9OrlvDMnRvP0YvmJQ3tOkJR/cVYxRPkVcWb9C7IEkSdiYNmQswyP4L4koeN0zzf8cBAwIWn9OKv7m8weUHFrqXf6ehy+CGLOXSzmWxmAVlPTbl6OQryjyXEwcMcFmetZqWhi6XZiFbRQcxC85lFPWd2ysik02i10r5zXqQyyWntPWZ8zVF+wPZ1Rq5y+vObc7zVmU00HGjblT2buknBrqq66g/kA2ZtV2qsaj/kI2ZuY3P4xoXix+MPNbS2Hsu865jL9emilwNcqvGYrGMmp9yeYu0mj80tqFqB5aGzHUDFtR+C1lqKmejbU10q/MzUe36/pv7Qa6Xs67uGKPLus3XJFcWtrmYlbfj49eG180uXsfFn+Wrg6Ko0WKF4LjDP+4uJDivNfHxEbo4nt9/2pSjks/HhnFr9Pw3BGWS8Pp1tFhd0mxkq8G9wq09veLIfpDg0iajV4MGelDLZUqCtTfGchIiTKbC0x8zuYPznd8Yry7379FfzIRX3FIdN9ahsHdrP3k2yIY6ssjDeDlBbLPGv3eQjZWMFjgMeU0yjb23HXtLfso17PxbGI3cpmWM/mLmbvF9fhlT1aGS/Xf1zYf/huC4RL40eYS/MxfbotDs3w6YfeCj9ttfeZtlchr4yAWFbq3K0DNaHM59YONniN6Lp8jcU+x7fJTcck2yzZpYMW+xbMBx4DhTbDVXjl4mQPJTLNi2KUcjX+V14OW67CcxbZCBbCU+NiwGpgZf0HOvFHLGeDVaI9lSD8YcMVkxsM0Ci68QWL5XX620lruZs44b69C189b6GQJkQxX5BBkI0x5+2GIF2biRp1iTTGNv52NvwXYHrELUP5BTyG1ehmRCG340xJv8gz0clxgLdZfljP7O4CY/yJAhnw+PpL9ZtdXIR5p0a+5nxuw/sZzE2Ph7zMuPcdMQyfT2N70P+HBPvFtWf1yS/STA5EVx92dezqXAyxff+TXx+a5w9DKxaoVeNp78TpSdv6BXGJVfnA4gXyNp8iS4hR6s4O54Rwt8hag+jWktdzNnHV9Vx631MwTIhlLZyifIT+ETZGOiCRp7dROqYLWAv1gh2K6ra+kVchuXgeKJ6vYb+4bJ66WR+RPZ2puFNIRblj1aYDXZ4d/+H3YonjjLfrOQ09y2Ot123ZczROsE4Ydf/aCPX7d8Q24wSdYIXXvtUF+4fdnqY4/P5RGB7J2EQTlS0hOO3J3nfs7d5VReZRQfeQiXG8nGk0XwTD8YGL1gAq5N+29sm54aWOvheocaLb4QultMy1vHNnJrkOq4bR1t/QRAF7rqK2TDvJz3p3iCLIdsjOLjIv7Dsh8kQ/5wrxEae8/YjL0VfGziCZbvRX06uU3LKH57C7b4jvST15L95zL/YE9MGC2wCo7YFesX/LcJltNlZVmF7DcjOU1tq9PtVX1Zwf4Ty8kqn2jzE+M77fT1X/2nLaaO3A2CmGGjeyow+ouZu8Ry7OAkzTvC4hDnXz4CAFyE6aHiCMHkhLFTpIYpDj5QPzGjuRwp/gdCd3xunxvGCN1p/jpw5GOThvDGeZluGCLArtp+I9l4MRc4xCc4YwfLRjmr9Zu1yUIPom1azwxGWHyF2I2ncBCDbdrIrUaq41a6KWRt4yed6aqvkA33n/n+1sdz3yxkfxp7k43hb5CG3lnO/AnXpsfrzmnsfczYK5F1PcZ4/gK20cits0eljGI19VuA6XSJIGYNPliei6CYKbwFmE4/sV9s4BdrpN/4R7Wy3wzlNLKtVrct/UNJubxiUwqMTfx9rjuI2c0fcjhJkrA/f/7cuBoTMkTeGKdVHwepPsvWHU4RhPIPO+/N79DxPXAch2z45JCNh81jY61In23aZ9ksySJ44xNWkgM0+uUPBHCxCR0mQhAEQRAEcUPOex4/WhDCCpokEwRBEARB3IJid4zxcoJ48I/Dfx9OkiRsMrH7upQgCIIgCIIgnpn/AFoHQ+TQuqjn4HHrVYl7QTYeNhRrCR7yh/5Ba5IJgiAIgiAIQgFNkgmCIAiCIAhCYPiTZO4cb0fc4LpynKThxuLSza8zRF5Zjk1arfCW5ZjWkee7x3nmjdjovpJXkF9Iczx+g3ZeLw48EwPb2ldbv00dBml9RGcbK9/ny2vh3yZ642UV7aSLE7o0ZRkavxuSjXU642lqe2dxWNenNWmmNqy1nbOTqX2JnN8w9mrjX72MXoy9T0c3ds4iTzPH0JSbJAkbLGnIXLgsTIt/xwEDAhbn/2ABwIK4zOpyaSrya8R8cQCGoiD+76a0WuktyzGvI2Whe2mzLQAYgHYXV7DRfTVvbkPBpooGxQEY3JCleSVVX1BJFtjZV1e/TR0maV3RjQ0Za7KNje/z5Vnpn8+j1VtetlsIl4bupRxdnNDGkKbmyPMOx8YanTVeaqpDuzis69PKtFY2lPuiso0d012sfRC/YuxtGJuqCunJ2Pt8dGPnmAWl7eLgEkeKfLIiS5sMe5Jcg1NEGjK30uG4NAl5RwZzg0B/XaVcXZpGNqtybOroSUe10b3gsGIb4uAyiAsXau0pJQ4YXNfCvrr6beowSOuQzoKt1jY2ftm2f/FyNOjNqr+3TRPzSfrakGxsGSNZJZ8uzrSNw13YpTmv2hfFMtrH0iaeb1L0hGNvw9gktKIfY+/T0ZGddX9XbHyhtMnwl1twZNEaW7c4F108Q3z/fUmT8bJCyhgOH69CocL54Lqzw/m0mnAty7GpQ6R4HeZFWf5KwZtj7lm8Gm+Lje79DdhhwR3TmeJ0LP/O8JO4mMkutD63PUO0BuKvmb6cin419dvU0ZjWU3S2sfXLNv0rz9C53ipxwiKtni/ER2Xb0wHauAXytovpLeKwrk9b9PdGG6p8sVaGuo1Elacce7VjUwOPGnufja7szP+dnnB0XzEGsP9cYrJaaI8Jf45J8nmzbiD8Khs8wuKQ4nVdrE9ZvyI9qJUx8v2G89QHxn4OZ5ogTBkO5Rnuxy2wYmCSYzG7xU73PNXBKQ9Ku3fJ2rbC0aFaZ1Qr9x272YdluzX1W9bRrv5+cc3EoW3/Mtbb6AUTXAbmLFpjiyNOaaUwSZwwSKtLhX+7IwIhuA7OxiY6qyFve1HAdXFY16dN+ruhDZt9UdNGosovGnuN499Dx15Cjo+PEFiOHTjTbd63swjrpNmezzFJHi1wYAwsnmA5Lu/U9pg7Y+xmKRhjSGc7jH/LXdxPBG+aIEwPWFSij4vX8T0EaKf7LPLyU4nKgJr9IAEw+2JgjIGxFU5jrpzjEmt85WlxgO1UNYnd43M3w9fCMhQ31W9cR8v6e0TNNnfBRm8+NmmIZJoPzO9YIXSFLNI4YZAmkv3D7hjgrRJch2hjA52JSNte0EUc1vXppv5uY8O2bSSq/JKx1zj+PXzsJVSMFodiHGfY+Bmi9+IpMvcBquxB23NMkkv8NwSV1ygBVoWnjharS9qTs90BqxBYfooWt1mecAUtdJ8HISBMuTvt0QIHJgYbrhw3vExK/A+Ervwp2H4+Bdo8FWqq37CO1vX3BKlt7oC13soBmzEcFsDpqBiY+Dhhk1aQ/dvhGLxVdDFYG5vqrEDW9hrXxGFdnzbs7yY21GHURqLKE4+9NvHv4WMvYcb+E8tJjI2/x7x46s/SEMm0fjP3XJPkWyCugeHXvejSuirHpo6CYLWAv1gh2K7Ntt55MOe79NqEVMP4Fe7xBO2bYQDAHt9bYFs8LXPGSxyxxbS8a2yhX7s6GurvOUrbdKI3XTlX6q2tPAakpyPcykxy2DY+Y6Czets7RNenjfv79dy0jYQ5jx57YT82DW3s7T1d2blChmidIPzw9b5QMujdLcQteipfKuZfm1a2NzL54lzy9eRgt4Djv85t2H2AsS6/sLXQvW7rNq19hZ0nTLdrsrFvQ/02dRildUQ3NmSN2+rZbwHHrPuX7jpBmsqXzcZ2tLaxwVfsg7GxRmdSFG3vMA7r+rQyrdN+et0uBaZ0F2sfxG8Yew23FS0y92TsfT66sjOXSb41nGAnPMsWcOX2MZDteZmGzD2nGTq71KHLPRxl+2rq0kTalmNahxjg838jiO/fUQ11n+8pW/+vusemqu1F+4RrmuUy16+ufuX2cE8ySW6yjZ3vF1j3L911NYEvcgqTJJ0d7WxssBXZgGys05kks7Lt3cVhXZ9Wp3XXT1tsLdmCZ5gUPfvY2xz/KsL3Z+x9OtS2k8dnnU9I+jcXA3nblr85SZKwP3/+iM+jiV+I4zgAgNw/iKHiOA7Z8MkhGw8birUED/lD/yhtQmuSCYIgCIIgCEKAJskEQRAEQRAEIfAfcHmsTBAA+cMzQDZ8fsjGw4dsSPCQP/SP/wBaB0Pk0Lqo54DWqz4/ZONhQ7GW4CF/6B+0JpkgCIIgCIIgFNAkmSAIgiAIgiAEhjVJziJ4qjPg26ZV8jjnM7wdL8Ll4JUMkVemieXo0mqVtCzHtI48391O+eLOPHccr3rCkC5NhcxOgl0qbePTKvaSFm6oXwdeRVhdWld19Bhdv7iFjWt2tOhfWnk05eh8zKYOm3LuiYlc1jFS13YL3dcrUfcTE38zaYeujr7a8NHQ2NuvsfdX0Y2ds8jTzCM05Q7nMJFyk2jVBtFt0vhsgfIkl8GeuGcJbDY0F08j4k9g0qVpyDdv5/PltqucYnQuN0+rnOp0je4rpyMJp5Ap0rqqo2uMbWiCql+0srGsL+rtaOz7DfKoy9H5mE0dFuV0gLmNzeSq9z19OdVT1HRpLWKkrJ8Y+ZtZrFf3xfvZ0CrWPhwae5vruOPY+8voxs7cISL8aYhFPlmRpU0GMUkuT/Zxg6B2ck3bNBHlqUziCS2V03N0aV2VY1PHIzuq7qQqg1Os4oDBdattE5y50r6aHizq1+nXVu6r6+ieLoOtul/UcmrbqOyLWjva+L5OHk05Oh+zqeOqcuwxtrGJXLK+J6KzU2c2bN/fzGO9po472nAokyIae4cw9j4zHdlZ97fipNHSJsNYbvGyQsoYDh+v3aVVyPCTuJj9HUmSfpBggpcyafSCCRL8ZA1pXZVjU4dI8XrSi7L8lYI3x9wzeWVhTxatsXVnkKpQk1bkQLQG4q9Z9Wd/A3ZY4HJZitOxjXAW+tVdd4s6eo2mX4g5m2xs3Bf5Qtv7fkUeXTlX+Filjq58tWsa5VL0PZHRX8zcLb7LwLH/vrRdl3ZNjNRQ8zdT/9LV0VcbPhIae3s/9j41XdmZ/zs94ei+Ygxg/7nEZMX3+TqDmCSPfF/ZiLZpVfJguHu3XF/ZZ/ZzONMEYcpwWBRaOG6BFQNjG/hd1VOsJxsvgfBLcDZdWiXbO3azj0aZ8oExxIePwukvA3MWrbHFEafUUv6iw0C2XkmX1lUdvcagXxjaWNkXu7KjpTzqyzkfu6IOo3IegCiXad8DRlgcUryuC19YvyI9Tyh1aRaY9BOF7o1jvUVf7KsN7wmNvS2419hLWODjIwSWYwfOdItgtcAoi7BOmvv3ICbJNyf7QQJg9sXAGANjK5zGA77j+4ngTROE6QGLSqRy8TruuK7RAgfGwOIJlqLOdGln9vjczfC10IfULPIwXk4QnwdfH5s0RDLNg+s7Vgjdlm04LrHGV277OMB2ygVqXVpXdfQVk35hZGMdHdrxSnnqPtauDuNy7kxdLrO+hyLv3BljN0vBGEM622F8fiqmS7OkqZ9c7W8GdaC/Nnw6aOwl7sRocSh8jGHjZ4jei6fI3AfBshtmmiQDReAVndrwtUoP2e6AVQgsP0WL3/CVv/+GQKUzTdp+PgUaXnfkAxYQpsJdeDlgMobDAjgdWwYiN7xMFPwPhC73JFOX1lUdfcWmX+jsb1RPB3a8Qh6lj1nW0aqcOyCTy6TvXQr4QYIAq8IZRovVpe26NFtM+8k1/tZQR19t+JTQ2Es8gv0nlpMYG3+PefHUn6Uhkmn9Bo0myU2Ia2D4dS+6tK7KsamjIFgt4C9WCLbrnj+t3ON7C2yLp4jOeIkjtphyd3TnJzq1QCrQVvfjV7jHE6TzVV1aV3UQVa70fSkN5Rj7WJPoHZXTNXK5mvteJ9jY8B79pKGOvtrwV0JjL9GVnStkiNYJwg9fb++SIexucUb3ZWPbNMbq2wkJXzwOdhsa/mttg50BYPOFrU5nDfpUIsqo3Sqt+iXrtbp3LwXVtq9SpXVVR9cY27CJe9i4wY7Gvt+2D9tsx6er48bb+okY29hUrsb4kMeWylZ95/y6NPsYKe0npv5mEOeUddzRhlaxtg/Q2NufsfeX0ZWduUzyreEEO2FIW8CduVVHZZctayDd17Hc79E2TaRtOaZ1iNvQ5P9GEN+ko+p0ptenssCKjPnerfX/qvuYFr83TtB0Oiz0JJbfkFbfuqhtHd3SZbC9tY0ZYw12NO9fbfpwk4+JNlbV0eirHWNqY2O5TLbXS0PmnssQJpO6NKsYqe4nRv4maUe9n8rruKcNBzcporG3V2Pv70JtA7sxuEwX4hM3/vB9vfzNSZKE/fnzR3weTfxCHMcBAOT+QQwVx3HIhk8O2XjYUKwleMgf+kdpE1qTTBAEQRAEQRACNEkmCIIgCIIgCIH/gMtjZYIAyB+eAbLh80M2Hj5kQ4KH/KF//AfQOhgih9ZFPQe0XvX5IRsPG4q1BA/5Q/+gNckEQRAEQRAEoYAmyQRBEARBEAQh8DyT5CyC5yjOfNelVfI45zO8HS9CZpvG/y6vBJFXliPK0zatnq/TE7Pawp2H7jhew+lDivZVyrj855WFVezSUIdKnqY6jHVvmNfEF4eCrl+IaP1BozehDq1vm+SV6d+mHRbl9KIfNmHVTwvEtnfZT1V1dJFWydMmFhBSaOxFr8bep6ObMTiLPHlsbvLRQR0moqTcQFq1ebTBZuOVU1hM0/KyKydN9enUH0vQ1Ybm4slVV5xUJ2Tkysl1fzk4zVXXYSOP5MS97k77MfTFK+nEhibo+gxPg/7VeqvaOL9OdwJjU16F/k3boS3HRtbreUQ/LTI1+3Dbflopol08V19Xvd5InhuejNlZrH04NPbm9GTsfUK6GYO5Q0T40xCLfLIiS5sMfpJcntbjBkHtVBtdmkj95BaDtIYjdoVSqmmVa9um1QTqaUdtqxcxH9c2K92byiPUYaV7fV4bX7yWewVbXZ9puJLTlUZvQjDT+ndDXp3+bdqhLMdG1g64fz819eEO+mkcMLiufTxXXCc0wlAeMRZ0yzNMimjsrQjU07F36HQ0Buv+VpzWW9pk+MstXlZIGcPh49UurUKGn8TF7O/IMs2C7AcJJngpixm9YIIEP9kVaU0Urw+9KMtfKXhzzD2TVxbdkkVrbN0Z5Oo1a19eRogPv8z3FzN3i++yIftvdR2G8tTqsNF9U15jXxwK7ftFRf86vfkbsMMClxpSnI6KQpvyKvVv2Q5VOTay9hRtPwWMfPj6fpohWgPx18yyfs11PIby1NpB1KGxV01Pxt7B09UYzP+dnnB0XzEGsP9cYrLi43adwU+SR76vbKAurUo+oO3eZevmNGmjF0xwCbhZtMYWR5zSKxrUFfs5nGmCMGU4LAotHLfAioGxDe4S+4s1Y+MlEH7pHbGhIPzbHRFUnHmExSHF67qwy/oV6aGhDq08sjq6w9wXh4Kuzyi40h9sJi5iXrX+7dphasdBTbIM7dLc9uv7aRa9Yzf7kMYnXf2664RSDOS5bSx4FmjsVdCHsZcQ8PERAsuxA2e6zft2FmGdNMfowU+SOyH7QQJg9sXAGANjK5zGxR2fLg0+NmmIZJp34nesELoPbEfJTwRvmiBMD1hUIpWL1/Ed5RgtcGAMLJ5gOb7iDjr7h90xwFvFmfeYO2PsZikYY0hnO4yb7tJ18kjrIJRo+4WCK/whizyMlxPETTdClnlbtaPL+vtAb/rpHp+7Gb4Wtlqzuc5AHooF94PGXuJOjBaHwo8YNn6G6L14isx9sCv78JImyUAxSIhOXT6m16Sdr80Vf1gAp+PjO8N2B6xCYPkpWpx7FXFP/DcEpq+pJGT/djgGb9U78OwHCQKsCsOMFivzOiTySOsg1DT1Cx2W/pBPOoEwbX4KY5MXwHXt6KL+PvHgfrqfT4EWT2+trjOQh2LBHaGxl3gE+08sJzE2/h7z4qk/S0Mk0/oNPE2Su0RcE8MjrqXh87ZNUxCsFvAXKwTbtdl2S4/EoH3p6Qj3xtFPWoeN7lvYiUCj3s5PZWuDZR2bvLfg0fU/muv66R7fW2BbPBl0xkscscW0cSu9ttepuUe8ITqGxt7n5CZjcIZonSD88PX2Lhn67hZndF89ar+IZPWtfvgvHnVpwteU12wRdpNtaPgv7pt0wDr8wlarM1l2XftUXw3nv1e2ADLdyqkmj/rL5G63gGNGdriWTmzYhI2NG/Iq9SZuUabDNK+of0tfVZZjI2sHPKKfMj5fzYc76KeNdVyZZiTPbXclKeks1vYBGntZb8beJ6TzMbiyrSDnR4KdSpvQJPmcxb0oRbGdjSwt78hFWuMAU+4bKds7sm1apRVCgM//jSC+e0fV6qxGU9sVk480ZO75Ov0ERS9P0/ZB8uvq2xMZ2OlZJsnMzsbN+q+n5Xve1v9T3syY5JXoXyeb6RZUNrJ2wWP66fkiiQ9300/1dbRLq9lQK4/NVpLteapJEY29rE9j7/PR5Rgs6d+cH/HxuvzNSZKE/fnzR/LsmvhtOI4DAMj9gxgqjuOQDZ8csvGwoVhL8JA/9I/SJrQmmSAIgiAIgiAEaJJMEARBEARBEAL/AZfHygQBkD88A2TD54dsPHzIhgQP+UP/+A+gdTBEDq2Leg5overzQzYeNhRrCR7yh/5Ba5IJgiAIgiAIQgFNkgmCIAiCIAhCYOCT5AyYe4DjAI6HyhE3+3nxe5FmcvrS3AGcefW3SjlFWecTXSLAK3735pffpaJq8rZNqwpa5IkMGtoxWQTPEY9zzBB5zvlMdE93/FAWwXPKvF71pKJKmnCKlu66eiWcPIKs3NntlXIqvxu0pW07+oxKN4BlmzT+wJfjRXIXl/qYLI+lr9zMxk3++ABkOtTZ17ScRh1axIK2dZj40KVwdSxoI+uvJEM0985+M+dsvZ97nC3mWp/K9vNzXm9etZsure4Pat/ly3EcrxYX5t5F1j1fhnEde8yN/I5ohU1c1YwBWeRJf28cW4Z7mEjKmAvG3DD/ZwDGEDBWnJzCAJbvDF3kg8uUu42nMWOBm1+DoJoWuopri3L5OkpZVLJK87ZNE4lz+ZXpzaDVhubl5t31Tb6rJw7pD+u4HLLGn4BVTcs3/S7L0V0nqcX0VDfxlKdqIZo62raje+xtqECrG7s2qf0hL6dyAlrtBA65j8nyXO0rHdnY+GS5lnTST218ny8paLCFUI55LGhbh4kPCWXrTlizlLUN7WJtXygOyij0VNoqTBlLi4MZgkJpeZpCh0Xe3G7VMrVprOxfpids5jZOy3LO110O/EivqaPsWyanVSoYtj/cEpu42jQGFH/zpyGy3Edl4aK0yXAnyeVEWObBcVBNC4sJsHxULCbHsklyOcEO6peJ9Ssn0w1526ap2nHHSXJ5GpIbBMKJQhanVtVOI1I7c+VUI911NYQ07QlIqnKEDthVO27A7YJt2zY1ncamtqPax8QquvCVK2xs5Y/X000/FTGQOQ4YXLeh//A6bKEH2zo6iwX3OW2PsYFPioqJp/QkSpFy0iwxpDgJ5f+tSztPbk1uQiuT7UtfuMQFMa1FHTRJvh02fdt0DBD/VtittMlwl1ukp/z/L6N6mv+W//+UAsiA3RFAAPiKstwASL8At1YJcASALbdsI5PX/zIBcARSA1n5vG3TmpgXSzT2wGUphlcs3Zg3XW3GywopYzh8vFZ/z36QYCI1TY3RX8zcLb7Ldx37b2zdGf6OAPgbsMMCl2JSnI4G14mI8oxeMEGCH8lrmyxaS8vJfw/xofKhtu0YEBXd2LTJxh9EVD4m0oGvXP54xqoAAA9mSURBVGVjG3+8N4Y6VPk+lwPRGoi/Zg1lcDq0tn2LOmzQxYJr/PQ3kZ5wBDAxUNT+e6spphowRsX4dkr1aZe+vcX0vIRC8Q7ef0MA4HhKkSHDv2Iu8ObX29G6DrHNc/6VfrkUw4PnyZb3EFps4qp2DOD6eXrC0X3FGMD+c4nJir9GwmCfJJdPVc/LJNzqk+LyaXKZ1niLJ3lqLC7bCLiyxKfT4tPrmqyKvG3TanBPksvrLu9RjfSAtnez4t1ecUcXF3ft0D2dywso7tr1d+Np6ErvFJuuM7obLV/LSe9STZ/8tm1Ht7SyoQ6tbsosmjZp/UH2Ok2ia+3TfxN5mmzThY0N/bEDOumnld/19s2zuflTN6UtJDq0jAWt6jD1oXNb9W98zONWe1rH2h5QPnENglJPrlxPxVNc0+UW+dKM4t+6tPIJcDEua5d0FPW45atzyVuq6uv5NnVcniSXvuNyY29g0LeG7A+3p11cFceAVOzXmqfIjD3Dk2QA+WPeFcBSIDgC0+KjuiwCplsgiC9p4xZPT0eLfJq98QGMgLcgr/Nfj5fnH5fA8pi3fSHcH7kz6G+ZupVjjS8wxsDiANup7qOHMXazFIwxpLMdxpK77SzyMF5OEJ/vFM2uM2a0wIExsHiC5VgoJ/uH3bF4+qCkbTsGgE43MGyT0h98bNIQyTR/+vKOFcLaGx07WvnK1Tbu2B/vSYN9c/b43M3wJcYUHpUOLWJBuzo69CFjWX87R2yxAmMp4uBY11MWwZsWT5GDVW0oAgD4G6RhACzHcJx3fPOvcnVphb8einHZL8blnWxcLuQ4BvFZVrWPc9jUcVbJEtNi7D1Ixt5evFUaHO3iqmxMGi0Oeb9mDBs/Q/RePEXmPtCUfXw+3EnyyyT//5swgU0B/NtJ0rZmO1zY1l/7XdITdHnbpjWx/W7Oc0vc8DLY+R8I3fI1lkD2gwQBVkXe0WKFQFgKkTs8EKaby4oZg+ta4b/V6/+3wzF4U67WuaodQ0KmG9M26fyhnKQxhsMCOB1dvI7bidjWV6628a388Z5I7Fuyn0+BhteSSh0axoKr6ujKh0zj1i9mVIxLwVt1AnnWUxbBGy/zlYoIEG/UvWq02BR2O2Dzlpd7Xv6gSTMl+7fDsSZr/vp+pBhfbeuosf0exs3xEGgRV43GpP0nlpMYG3+P+TRBmDKwNEQyrU/AhztJHjesUbwXpbV+EgAuoAvMurxt02oEQFzcFDzqEcj4Fe7xZLR0uonzHSE7yJ9GmCCuQbZce5iejnDbztrKKrtoR88wbpONP1yxLvQaHXdh4+dlj+8tsC2e1DrjJY7FWk3+yYtUh8a2v6IOEZ0P6WJBh3HrqRm/1j/fOZM/ocsnyK7VA4GsGN9k5tWlXUtSOMP1dQSIi7F3Ta8fHoLZGJAhWicIP/xq/1d9qzTYNcmV7dFYdb2wbi1xU3n8muTKGuD0ss1crf60f1vAVdpstvMFulqTzPJtVc7rsrRbS+XrjapfGPNfoarWcmmuk6Dc9kmUrbZOyW6tqn07uqeVDWXodGPZJrU/VNeHi1tynWlak3yVr3RgY0t/vJZO+mmj7xuWk/+o1KF5LGhbh6EPsXq6bAs4a1lb0DrW9gJ+6zRhm7fzOmSD/hTzu0tcymxOk61XVthJ2AKuurZYswWcTR3C7hbVOsx2vhi2P9wSi7hqOibFAdfn1TsUlTYZ8CSZMcbiYmIr+3AvvKS5QbsP9xhjLOQ+ABTLSS3q0OVtmybqgp8IV24U7j9Jriy2bwqY5w+Hqh84lB9riP9Vt36qXyen/ICiHuz4Bf31DqjecqYyoF7Tjo7pMtiqdGPfJo0/cAOrcjBpmCRf5yvX27i5jm7pqp/qfd+8HP32aRaxoG0dGh+q2VATC1rJ2oLhT4piFrgXX7/MX+X9ULVdXBxc/M8NRLup09KQ+xjPDRq2LQyZ6yrypuGlHW7A4kpXN61DmAhzE3OaJHeAJq7yfdtsTJLEEMWNXfmbkyQJ+/Pnj+q5NPGLcBwHAJD7BzFUHMchGz45ZONhQ7GW4CF/6B+lTYa7JpkgCIIgCIIgbgRNkgmCIAiCIAhC4D/g8liZIADyh2eAbPj8kI2HD9mQ4CF/6B//AbQOhsihdVHPAa1XfX7IxsOGYi3BQ/7QP2hNMkEQBEEQBEEooEkyQRAEQRAEQQg8xyR57gDOvPrbfg44Tv7fPNJcnAFz75LXmwP8iSu6crII8BTX1arR5G2bVm1wkUfX1jvBnYXO/+c1nUKURfDEc9mzCB5XRuVsdT7Ni7Tq19ahTcsQeWX9DWfGm8rqeA87DLFbeN0Y2Bew17+gU72ddfIY2FEnm1E5Fr7SF2z0a+zf+jRtHZXYoegn1n24lkltJyt/I/bzug6z/bwS6+Y6Y9TGCs7mWYR5aSdvjr0wLirTBLKIk0fMq6nfvB17zMlXbo9J39bEjyzyNPFJU+6gDxNJY8YCtzjsQ3NSnu6kukpeVj2pTltOz0/cawFutaG50clV5Qb/fL78t8vhOEHtJKPKSTwGO//rTk6SpelO55LJr5O1TOvlaWwtiANxA33TA13M9V89Ham9PCZ21J+q1VyOua9cT2c2NtavuX9X0yzqEH1IGjda+JAsj8pOFv52DTeLtfcijVl4PuxDOLURwil2mriQx0JZuuY0PG1arQLtwR7K+q3aYXZgiI7B+8MdaOzb2vjBHSISBxVbxYH80KDSJgOeJMeXk/bESXLoVo+hFv+tLbaYGMcN5ZQn2pUW0dWhy9s2TaWP3k2ShQFUQnnqlxsE9WNzVUdE107k0p34xZfnyk9uk6YJZepOfeta1iu4T7C1a4PSxufi5Lapn5bWRh4DO+p8w6gcC1/pgK5sbKxfnX/r0mzqqFda0WlbH9KVKdqpvax2DHtSVN6ouMVJaOJR5+Ixwqr4X04+JfZK+WOphcmsLk2LWJ+mfqt20CT55hj17dpF8iOnxb8VdittMuzlFm4ApF+AK/x+Olb//TIBcARSgzK/t2blpKfit1FzHbq8bdOamBdLNPbAZSmGVyzdmDdd3RlZtMbWDfHhazK9rJAyhsPHa/V3fwN2WGB0/iGtmcRCEkRrIP6amadlP0gwOasfoxdMkOBH9k5NJ+voL2buFt/l+5z9N7buDH9HtVKGg6ibJlQ2zgtT2CbDT+JiZqIonTyNdtT5hmE5Nr7SGyz0q/NvbT+1qEOULlpX+0krHxKz6ezUXtZfhxsgTr8wE8de/w0BgOMpRYYM/3ZHAAHepPG/9JMtpuclDUWHSU84ApgUhhoVY98pbUjTkRX1BW/wm+q3akeVfAlK+Uq/XIrhwfMGtAyrVxj2bfEqPn7w/Tw94ei+Ygxg/7nEZMXHrjoDniT7wGEDaeveAgBH4F8GILtMfJtGrP0c2AKAC4wbyvlJ5GXI6tDlbZumI/LydoQpwHfqI4AvBrCN/vrOyINL0OCEI9/Xpp9L4yfcoxdMcJl4ZtEaW02gzKJ37GYfkMU4XVpbqjcHIywOKV7XxVqp9SvSg14nvacINFCt8xLQ2Vit/3wQ270brOW2lMes/mfHQr8CupvfalqLOop1weMlEH5d+kk7H7KhvT5+Fz42hw18qTF8bOIA7naKsTPG8ugiTDdyu2Q/SAC4QQzGUsTBEdvpO6IMyBRjX/KTadPU7DEfT7F1A8Sl02rqt2oHRxp5mG4BN0yxEcbe2RcDY81lEFWs+7Y0fvj4CIHl2IEz3eZzkizCOml4gIdBT5I1+BsgDIDlGHDeUX/ULCGLgGkxCQ5W+eS7TTmP5rgElkcgiIGFEMXcmfym4lZk/7A7mt19NxYVeRgvJ4gPF6ffpCGSaT6gvWOFUGmePT53M3yJ+mhM60rWPebOGLtZCsYY0tkO42d4onBcYo0vMMbA4gDbaZtJhUb/xSCWDy4MjK1wGmv01kqe7u0/GGz1W15W829NWps6RgscGAOLJ1gayNOZDVvqg+DIInjTLY7cxFNpw8LOh40PYAS/eCi1+3eLOxMfG8YQT7aYjou4oKvfph0lxyWmxdh7kIy99IKiDS36tiJ+jBaHol8zbPwM0XvxFJn72E/2YOU5J8kAsNgAjAHsALxN8t9U74azCBgvi38EqNwCqsp5mcjLktWhy9s2rYntd3OeG5P92+F4frV1RTmRl98VinfyZWdgDIcFcDq6eB3Xr9/Pp4DiabYurTNZsx8kCLAqOvposULQ+1fxBrjhJXj5Hwhdg1eeAlr9jxY4sINwr6fRWwt5urb/oLDVLzR9UZXWoo4z/ptRP+nMhtfISgAoYj6A4I2feHJLzQwZKca+yctIm9aE6UT8qnZsv+nGqiOu6tu6+LH/xHISY+PvMZ8mCFMGloZIpvUboeedJPP8JDgvoaiRAe/lBNkFUs1SBFk5pQW0dRjkbZtWIwDivEM/+l1hejrClc1aLTg/maoNXmJG1ZrUPb63wLZ44uyMlzgWa9Dme10a6utKG9bhGsv6DIxf4R5PRsvj1TTovyt5lHa0rF/nD5a+MkR0/v043+/QhkTvKJdQZMXYxw8nurQmTCbU9gSIi7F3Tet0OqDD8aFChmidIPzw9TG8ZLi7W5QUW6NVtoDjd4Xgt1GTUO5mUe5oUUnTldPzLeD4rewMd75Ap1/YVr9wN7tE2BFAu61Y9St14y23dLsOSNKMt/XSyprrovqldP93PmiishOA0TZ/zE7/YpmaL5Gb5DGyo8GOFE+1BZyNfnX+rUuzqcM0r2UfrlejsJOlv11Dt7H2UUh2hxC2Tsu37dL5Rtlny7zCzhNXbgGX6urQpdm0Q9jdoprXbOeL5/CHG9PUt037b2WbR8UOGOwptoArkUySGeP2TwZjgWZyGOCSj//vvG+yppw0LOoGY26g32JOl7dtWgVhIlxuH1fsD3n/SXKLbc4k2zGdHZX7r7ofa/G76WBmPcCW2x3J91AuJ2WNspZBF/p9Q7vgfsG2HCSFtmovsdN/ufWSTP928qjtqKu/viWYrhyDOjqiKxub6lfn302+b2NDo7wtbnRNbWjnb+15jkmRYgu1OGRu2Q/dQBvr0jC4xEUxbxqygCsnNk0TZIxDt1IHn1dbv3E7hIlww97MMp7DH26MQd9u7r+SeQk3j+DHjPI3J0kS9ufPH9Pn1MQT4zgOACD3D2KoOI5DNnxyyMbDhmItwUP+0D9Km/yONckEQRAEQRAEYQFNkgmCIAiCIAhC4D/g8liZIADyh2eAbPj8kI2HD9mQ4CF/6B/0JJkgCIIgCIIgBP4PZa7MtY997b4AAAAASUVORK5CYII=" alt="image.png"></p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Exempel-3">Exempel 3<a class="anchor-link" href="#Exempel-3">&#182;</a></h1><p>Exempel med bra underlag till ingångsvärden av stål och betong totalenterprenad.
Fördelen med denna metod visas tydligt då inte bara prognoserade preiser är inom väldigt liten marginal, utan även ge prognos till en hela enterprenad inte bara viss material typ - detta är möjligt just tack vare linjära relationen av ingående värden, alltså alla förändringar speglas i prisen då ändring av en viss komponen linjärt ändrar kostnader totalt.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><img src="data:image/png;base64,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" alt="image.png"></p>

</div>
</div>
</div>
    </div>
  </div>
</body>

 


</html>
