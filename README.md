<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>HTML</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	text-indent: -1.7em;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(96, 96, 98, 0.93);
	fill: rgba(96, 96, 98, 0.93);
}
.highlight-brown {
	color: rgba(174, 102, 29, 1);
	fill: rgba(174, 102, 29, 1);
}
.highlight-orange {
	color: rgba(210, 82, 22, 1);
	fill: rgba(210, 82, 22, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(62, 143, 53, 1);
	fill: rgba(62, 143, 53, 1);
}
.highlight-blue {
	color: rgba(33, 131, 190, 1);
	fill: rgba(33, 131, 190, 1);
}
.highlight-purple {
	color: rgba(151, 93, 190, 1);
	fill: rgba(151, 93, 190, 1);
}
.highlight-pink {
	color: rgba(203, 62, 132, 1);
	fill: rgba(203, 62, 132, 1);
}
.highlight-red {
	color: rgba(208, 60, 60, 1);
	fill: rgba(208, 60, 60, 1);
}
.highlight-gray_background {
	background: rgba(234, 234, 235, 0.93);
}
.highlight-brown_background {
	background: rgba(213, 130, 38, 0.13);
}
.highlight-orange_background {
	background: rgba(252, 103, 27, 0.13);
}
.highlight-yellow_background {
	background: rgba(253, 183, 63, 0.13);
}
.highlight-teal_background {
	background: rgba(76, 169, 66, 0.13);
}
.highlight-blue_background {
	background: rgba(45, 159, 226, 0.13);
}
.highlight-purple_background {
	background: rgba(187, 123, 230, 0.13);
}
.highlight-pink_background {
	background: rgba(255, 85, 163, 0.13);
}
.highlight-red_background {
	background: rgba(255, 82, 71, 0.13);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(96, 96, 98, 0.93);
	fill: rgba(96, 96, 98, 0.93);
}
.block-color-brown {
	color: rgba(174, 102, 29, 1);
	fill: rgba(174, 102, 29, 1);
}
.block-color-orange {
	color: rgba(210, 82, 22, 1);
	fill: rgba(210, 82, 22, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(62, 143, 53, 1);
	fill: rgba(62, 143, 53, 1);
}
.block-color-blue {
	color: rgba(33, 131, 190, 1);
	fill: rgba(33, 131, 190, 1);
}
.block-color-purple {
	color: rgba(151, 93, 190, 1);
	fill: rgba(151, 93, 190, 1);
}
.block-color-pink {
	color: rgba(203, 62, 132, 1);
	fill: rgba(203, 62, 132, 1);
}
.block-color-red {
	color: rgba(208, 60, 60, 1);
	fill: rgba(208, 60, 60, 1);
}
.block-color-gray_background {
	background: rgba(234, 234, 235, 0.93);
}
.block-color-brown_background {
	background: rgba(213, 130, 38, 0.13);
}
.block-color-orange_background {
	background: rgba(252, 103, 27, 0.13);
}
.block-color-yellow_background {
	background: rgba(253, 183, 63, 0.13);
}
.block-color-teal_background {
	background: rgba(76, 169, 66, 0.13);
}
.block-color-blue_background {
	background: rgba(45, 159, 226, 0.13);
}
.block-color-purple_background {
	background: rgba(187, 123, 230, 0.13);
}
.block-color-pink_background {
	background: rgba(255, 85, 163, 0.13);
}
.block-color-red_background {
	background: rgba(255, 82, 71, 0.13);
}
.select-value-color-gray { background-color: rgba(234, 234, 235, 0.93); }
.select-value-color-brown { background-color: rgba(213, 130, 38, 0.13); }
.select-value-color-orange { background-color: rgba(252, 103, 27, 0.13); }
.select-value-color-yellow { background-color: rgba(253, 183, 63, 0.13); }
.select-value-color-green { background-color: rgba(76, 169, 66, 0.13); }
.select-value-color-blue { background-color: rgba(45, 159, 226, 0.13); }
.select-value-color-purple { background-color: rgba(187, 123, 230, 0.13); }
.select-value-color-pink { background-color: rgba(255, 85, 163, 0.13); }
.select-value-color-red { background-color: rgba(255, 82, 71, 0.13); }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="d0dad24a-f3fb-4933-b197-b7b3c4c1cdeb" class="page mono"><header><div class="page-header-icon undefined"><img class="icon" src="HTML%20b70af17d928049de8f452bb490681dae/HTML_logo.png"/></div><h1 class="page-title">HTML</h1><table class="properties"><tbody><tr class="property-row property-row-select"><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.4);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesSelect"><path d="M7,13 C10.31348,13 13,10.31371 13,7 C13,3.68629 10.31348,1 7,1 C3.68652,1 1,3.68629 1,7 C1,10.31371 3.68652,13 7,13 Z M3.75098,5.32278 C3.64893,5.19142 3.74268,5 3.90869,5 L10.09131,5 C10.25732,5 10.35107,5.19142 10.24902,5.32278 L7.15771,9.29703 C7.07764,9.39998 6.92236,9.39998 6.84229,9.29703 L3.75098,5.32278 Z"></path></svg></span>Level</th><td><span class="selected-value select-value-color-blue">Introductory</span></td></tr><tr class="property-row property-row-relation"><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.4);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesRelation"><polygon points="4.5 1 4.5 3 9.586 3 1 11.586 2.414 13 11 4.414 11 9.5 13 9.5 13 1"></polygon></svg></span>Related to Coding Projects (Files)</th><td></td></tr><tr class="property-row property-row-multi_select"><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.4);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesMultipleSelect"><path d="M4,3 C4,2.447715 4.447715,2 5,2 L12,2 C12.5523,2 13,2.447716 13,3 C13,3.55228 12.5523,4 12,4 L5,4 C4.447715,4 4,3.55228 4,3 Z M4,7 C4,6.447715 4.447715,6 5,6 L12,6 C12.5523,6 13,6.447716 13,7 C13,7.55228 12.5523,8 12,8 L5,8 C4.447715,8 4,7.55228 4,7 Z M4,11 C4,10.447715 4.447715,10 5,10 L12,10 C12.5523,10 13,10.447716 13,11 C13,11.55228 12.5523,12 12,12 L5,12 C4.447715,12 4,11.55228 4,11 Z M2,4 C1.44771525,4 1,3.55228475 1,3 C1,2.44771525 1.44771525,2 2,2 C2.55228475,2 3,2.44771525 3,3 C3,3.55228475 2.55228475,4 2,4 Z M2,8 C1.44771525,8 1,7.55228475 1,7 C1,6.44771525 1.44771525,6 2,6 C2.55228475,6 3,6.44771525 3,7 C3,7.55228475 2.55228475,8 2,8 Z M2,12 C1.44771525,12 1,11.5522847 1,11 C1,10.4477153 1.44771525,10 2,10 C2.55228475,10 3,10.4477153 3,11 C3,11.5522847 2.55228475,12 2,12 Z"></path></svg></span>Source</th><td><span class="selected-value select-value-color-gray">W3Schools</span></td></tr><tr class="property-row property-row-select"><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.4);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesSelect"><path d="M7,13 C10.31348,13 13,10.31371 13,7 C13,3.68629 10.31348,1 7,1 C3.68652,1 1,3.68629 1,7 C1,10.31371 3.68652,13 7,13 Z M3.75098,5.32278 C3.64893,5.19142 3.74268,5 3.90869,5 L10.09131,5 C10.25732,5 10.35107,5.19142 10.24902,5.32278 L7.15771,9.29703 C7.07764,9.39998 6.92236,9.39998 6.84229,9.29703 L3.75098,5.32278 Z"></path></svg></span>Status</th><td><span class="selected-value select-value-color-orange">Ongoing</span></td></tr><tr class="property-row property-row-relation"><th><span class="icon property-icon"><svg viewBox="0 0 14 14" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.4);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesRelation"><polygon points="4.5 1 4.5 3 9.586 3 1 11.586 2.414 13 11 4.414 11 9.5 13 9.5 13 1"></polygon></svg></span>Tags</th><td></td></tr></tbody></table></header><div class="page-body"><h1 id="b0b454c7-43f1-48bb-b736-4640dc429f0b" class="">HTML básico ☑️</h1><p id="f5fdfa91-5f02-4f2b-b9ab-7f950478a3c9" class="">Neste capítulo, mostrarei alguns exemplos básicos de HTML.</p><hr id="2eee1ab5-628d-4add-9a3a-1a13c7a013f8"/><ul id="dfcc787f-ebab-4221-ae63-36ffe2cfb46d" class="toggle"><li><details open=""><summary><strong>Documentos HTML </strong>🆗</summary><h2 id="662771a7-4614-4a76-9a38-6db82940124a" class="">Documentos HTML</h2><ul id="b482b839-faa0-406c-b370-f7cb3dbd8c0b" class="bulleted-list"><li style="list-style-type:disc"><code>&lt;!DOCTYPE html&gt;</code> declara para o navegador que o tipo do documento é HTML.</li></ul><ul id="dad9d768-f58c-4c54-9b87-f162fcc5ec5f" class="bulleted-list"><li style="list-style-type:disc">O elemento raiz de uma página HTML começa com a tag <code>&lt;html&gt;</code> e termina com <code>&lt;/html&gt;</code>.</li></ul><ul id="c23c1a1d-bfb3-4227-a02e-66aff725e7f7" class="bulleted-list"><li style="list-style-type:disc">A parte visível para o usuário do documento HTML se encontra entre <code>&lt;body&gt;</code> e <code>&lt;/body&gt;</code>.</li></ul><pre id="131c9100-a0fe-44ff-b8e2-badd9e50c238" class="code"><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;body&gt;
	&lt;p&gt;Conteúdo visível para o usuário.&lt;/p&gt;
&lt;/body&gt;
&lt;/html&gt;</code></pre><figure id="b70af17d-9280-49de-8f45-2bb490681dae" class="image"><a href="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_08-39-54.png"><img style="width:222px" src="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_08-39-54.png"/></a></figure><hr id="b54fc695-4fd6-4142-8856-0c0d44476904"/></details></li></ul><ul id="d1741258-0a57-4eca-98ec-01647f949626" class="toggle"><li><details open=""><summary><strong>&lt;!DOCTYPE html&gt; </strong>🆗</summary><h2 id="f30003c1-3b5a-4ad8-a8f6-a01e06df2ba9" class="">&lt;!DOCTYPE html&gt;</h2><ul id="5699b51c-4d37-4972-bef7-bfda9ae69e0c" class="bulleted-list"><li style="list-style-type:disc">Representa o <code>tipo do documento</code>.</li></ul><ul id="47ac5683-9b09-4ae1-87f9-84e2f43350dd" class="bulleted-list"><li style="list-style-type:disc">Ajuda os <code>navegadores</code> a exibir as páginas web corretamente.</li></ul><ul id="b8b10aa8-b6e5-4725-9a20-028dd9771115" class="bulleted-list"><li style="list-style-type:disc">Deve aparecer <code>uma vez</code>, <code>antes</code> de qualquer tag HTML.</li></ul><ul id="3f8587b9-ff5d-41c4-91f5-5c81bf149f6e" class="bulleted-list"><li style="list-style-type:disc"><code>Não diferencia</code> maiúsculas de minúsculas.</li></ul><pre id="70460f1b-560e-49c9-8008-6e846b40c16a" class="code"><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
...
&lt;/html&gt;</code></pre><hr id="5e02c057-1abb-48c6-834f-bb78f2a0744d"/></details></li></ul><ul id="3d9dc114-a62f-4a9d-9869-07e789cc2e13" class="toggle"><li><details open=""><summary><strong>Cabeçalhos HTML </strong>🆗</summary><h2 id="419beb0e-38c7-42dd-ac4b-06ded2a8148a" class="">Cabeçalhos HTML</h2><ul id="de5eba9d-3a58-49d7-bed4-cdca24faf260" class="bulleted-list"><li style="list-style-type:disc">Cabeçalhos são <code>títulos</code>.</li></ul><ul id="ede742a9-99a1-42d8-8ca6-56c2ff134987" class="bulleted-list"><li style="list-style-type:disc">O maior cabeçalho é o <code>&lt;h1&gt;</code> e o menor é o <code>&lt;h6&gt;</code>.</li></ul><pre id="cc40474c-355e-4595-8d9b-d8c4d2102af5" class="code"><code>&lt;h1&gt;Cabeçalho 1&lt;/h1&gt;
&lt;h2&gt;Cabeçalho 2&lt;/h2&gt;
&lt;h3&gt;Cabeçalho 3&lt;/h3&gt;
&lt;h4&gt;Cabeçalho 4&lt;/h4&gt;
&lt;h5&gt;Cabeçalho 5&lt;/h5&gt;
&lt;h6&gt;Cabeçalho 6&lt;/h6&gt;</code></pre><figure id="77ddac9f-f333-4658-b22d-5df7cc0e86c8" class="image"><a href="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_08-38-30.png"><img style="width:186px" src="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_08-38-30.png"/></a></figure><hr id="4874c6d0-8ae2-4189-a920-ea8173e307a0"/></details></li></ul><ul id="89279aec-a4f1-42d5-83fd-65a65069e131" class="toggle"><li><details open=""><summary><strong>Parágrafos HTML </strong>🆗</summary><h2 id="ec6927bf-39ef-495f-8d99-251851baab5c" class="">Parágrafos HTML</h2><ul id="4ae201bf-9229-45ce-9646-eabf84bafd38" class="bulleted-list"><li style="list-style-type:disc">Parágrafos são <code>blocos de texto</code>.</li></ul><pre id="4ae77bab-cca2-4628-821b-7d5316ddbad3" class="code"><code>&lt;p&gt;Este é um parágrafo.&lt;/p&gt;
&lt;p&gt;Este é outro parágrafo.&lt;/p&gt;</code></pre><figure id="10fc8b6c-4d0f-4fef-b96a-34b805a50b1a" class="image"><a href="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_08-44-13.png"><img style="width:162px" src="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_08-44-13.png"/></a></figure><hr id="b105c28a-97cb-4edf-8cf8-1f9e790d4ab2"/></details></li></ul><ul id="714474bc-1e14-49da-9911-6cc206e5917f" class="toggle"><li><details open=""><summary><strong>Links HTML </strong>🆗</summary><h2 id="311073b2-0377-4538-aabc-4f617a5932d6" class="">Links HTML</h2><ul id="b923d97d-788d-4322-8839-4be684d884d3" class="bulleted-list"><li style="list-style-type:disc">Os links vão permitir que o usuário <code>acesse outras páginas web</code> ou <code>outros recursos</code>, como imagens, vídeos, áudios, PDFs etc.</li></ul><ul id="e766c8c7-4af5-4c79-80df-51e5d25d4d72" class="bulleted-list"><li style="list-style-type:disc">Os links são definidos pela tag <code>&lt;a&gt;</code>.</li></ul><ul id="86e2928d-428a-48e1-a3ae-874b741fb5cf" class="bulleted-list"><li style="list-style-type:disc">O atributo <code>href</code> especifica o destino do link.</li></ul><ul id="66c95be0-6829-4d43-9ad4-b58944a175d9" class="bulleted-list"><li style="list-style-type:disc">Os <code>atributos</code> são usados para fornecer informações adicionais sobre os elementos HTML.</li></ul><pre id="bb6b7281-d8e3-4f19-b2d8-ed29a0df43ec" class="code"><code>&lt;a href=&quot;https://www.google.com&quot;&gt;Clique aqui!&lt;/a&gt;</code></pre><figure id="c60cf7cb-fe94-4ae8-b152-027ee04fc285" class="image"><a href="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_09-18-11.png"><img style="width:93px" src="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_09-18-11.png"/></a></figure><hr id="b41149aa-bffd-4d39-8ab0-394da547ef61"/></details></li></ul><ul id="a0c4ca87-0479-44bb-8f9a-cfa5be50b7db" class="toggle"><li><details open=""><summary><strong>Imagens HTML </strong>🆗</summary><h2 id="ee4368de-afe4-4681-9d4c-b70431bf64e2" class="">Imagens HTML</h2><ul id="dc6e96ed-d772-46f3-bae5-740ef99260d8" class="bulleted-list"><li style="list-style-type:disc">As imagens HTML são definidas pela tag <code>&lt;img&gt;</code>.</li></ul><ul id="131ab2d3-30f2-4364-a115-057d91c2d009" class="bulleted-list"><li style="list-style-type:disc">O atributo <code>src</code> informa a localização do arquivo de origem da imagem.</li></ul><ul id="9bc54184-f0a1-4aab-b4c3-d297d34408e0" class="bulleted-list"><li style="list-style-type:disc">O atributo <code>alt</code> mostra um texto alternativo (para caso a imagem não possa ter sido carregada por algum motivo).</li></ul><ul id="bb665a5a-2e2c-4fc7-8b28-bc1ce6535928" class="bulleted-list"><li style="list-style-type:disc">O atributo <code>width</code> define a largura (horizontal) da imagem.</li></ul><ul id="64edc529-b968-44a2-bd4e-28fb39312139" class="bulleted-list"><li style="list-style-type:disc">O atributo <code>height</code> a altura (vertical) da imagem.</li></ul><pre id="72fdc076-c366-45bf-b9f8-48284b916c0f" class="code"><code>&lt;img src=&quot;http://is.am/cao.jpg&quot; alt=&quot;Cãozin&quot; width=&quot;300&quot; height=&quot;200&quot;&gt;</code></pre><figure id="b0df7384-54e6-4cd2-aa7e-1f2ed1bf027e" class="image"><a href="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_09-39-21.png"><img style="width:313px" src="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_09-39-21.png"/></a></figure><hr id="37d42385-d243-4d50-8709-13cf848d6858"/></details></li></ul><ul id="d2380532-bcdc-442d-ad55-66f14a3f6446" class="toggle"><li><details open=""><summary><strong>Código-fonte de uma página web </strong>🆗</summary><h2 id="7dea35a7-0a1a-4ee7-a2d4-c9c12373933c" class="">Código-fonte de uma página web</h2><ul id="08c51e70-65a6-4586-aaa0-542546f3d737" class="bulleted-list"><li style="list-style-type:disc">Para ver o código-fonte de uma página web: <code>Ctrl + U</code> ou <code>Botão direito do mouse</code> &gt; <code>View page source</code>.</li></ul><figure id="8a67f29b-31a3-412c-ae5f-6639eda499d0" class="image"><a href="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_09-48-40.png"><img style="width:1366px" src="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_09-48-40.png"/></a></figure><figure id="f9c2a6ac-3486-4890-ae8c-fb68ae4b7307" class="image"><a href="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_09-48-43.png"><img style="width:1366px" src="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_09-48-43.png"/></a></figure><ul id="918ab821-5e3a-4de7-b31a-0d9e3874d7f5" class="bulleted-list"><li style="list-style-type:disc">Para examinar os componentes da página web sem sair da página: <code>Ctrl + Shift + I</code> ou <code>Botão direito do mouse</code> &gt; <code>Inspect</code>.</li></ul><figure id="0e328497-4046-4ed7-bd44-d42a8e9a55cd" class="image"><a href="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_09-48-57.png"><img style="width:1366px" src="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_09-48-57.png"/></a></figure><figure id="cb9c9455-0328-4b65-a3c0-0775e16564a5" class="image"><a href="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_09-49-07.png"><img style="width:1366px" src="HTML%20b70af17d928049de8f452bb490681dae/Screenshot_from_2021-10-09_09-49-07.png"/></a></figure><hr id="fc1f607c-d730-49f8-be4b-c184b22f3af1"/></details></li></ul></div></article></body></html>
