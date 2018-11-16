<!-- Section Intro -->
<div class="panel section-intro extra-space bg-dark">
<div class="grid-container grid-x grid-padding-x align-center">
<div class="cell small-12 medium-6 large-5" markdown="1">

## Why Create Extensions on&nbsp;Firefox?

</div>
<div class="cell small-12 medium-6 large-5" markdown="1">

Build on the web’s most customizable browser. Get your great idea into the hands of millions of users. Join an international community of developers in the movement to put people in control of their online lives. __(P.S. There’s no cost to participate!)__

[Learn more about extensions](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/What_are_WebExtensions)

</div>
</div>
</div>
<!-- END: Section Intro -->


<!-- Section Tiles -->
<div class="section-tiles bg-grey">
<div class="tiles-outside">
<div class="grid-container grid-x grid-padding-x align-center">
<div class="cell small-12 medium-8 large-6 text-center" markdown="1">

## Cool Things Extensions Can Do

</div>
</div>
</div>
<div class="tiles-container mobile-slider">
<div class="grid-container grid-x grid-padding-x align-center">

<!-- Tile 1 -->
<a href="https://www.firefox.com" class="cell small-12 large-4 tile tile-block-link">
<div class="block-link" markdown="1">

![Tinker with Tabs](assets/img/Tinker-with-Tabs.svg "Tinker with Tabs")

#### Tinker with Tabs

Your extension can control browser tabs. Use the API to open, close, move, hide, and perform other tab management actions.

<span class="block-link-inline">Learn more about tabs</span>

</div>
</a>
<!-- END: Tile 1 -->

<!-- Tile 2 -->
<a href="https://www.firefox.com" class="cell small-12 large-4 tile tile-block-link">
<div class="block-link" markdown="1">

![Transform Web Content](assets/img/Transform-Web-Content.svg "Transform Web Content")

#### Transform Web Content

Inject JavaScript into web pages and your extension can change page colors, augment text, remove distractions, and much more.

<span class="block-link-inline">Learn about enhancing content</span>

</div>
</a>
<!-- END: Tile 2 -->

<!-- Tile 3 -->
<a href="https://www.firefox.com" class="cell small-12 large-4 tile tile-block-link">
<div class="block-link" markdown="1">

![Add Innovative Features](assets/img/Add-Innovative-Features.svg "Add Innovative Features")

#### Add Innovative Features

Think the browser is missing a feature, such as a built-in calculator, music streaming, or language translation? Add a toolbar button to expose your extension's new capabilities.

<span class="block-link-inline">Visit example</span>

</div>
</a>
<!-- END: Tile 3 -->

</div>
</div>
<div class="tiles-outside">
<div class="grid-container grid-x grid-padding-x align-center">
<div class="cell small-12 medium-8 large-6 text-center" markdown="1">

[View more extension code examples](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Examples)

[Explore live extensions](https://www.firefox.com)

</div>
</div>
</div>
</div>
<!-- END: Section Tiles -->


<!-- Section Anatomy of an Extension -->
<div class="section-anatomy panel bg-grey">
<div class="grid-container grid-x grid-padding-x align-center">
<div class="cell small-12 medium-6 large-5" markdown="1">

## Anatomy of an Extension

</div>
<div class="cell small-12 medium-6 large-5" markdown="1">
	
An extension is a simple collection of files that modify the browser’s appearance and behavior. It can add user interface elements, alter content, or perform background tasks that enhance browsing.

[Learn more about extension anatomy](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Anatomy_of_a_WebExtension)

</div>
</div>
<div class="grid-container grid-x grid-padding-x align-center">
<div class="cell small-12 large-10">

<div class="anatomy-container">
	<div class="anatomy-illustration">
		{% include home/anatomy.svg %}
		<p class="manifest show-for-medium"><img src="{{ "/assets/img/icons/manifest.svg" | relative_url }}">Manifest.json</p>
	</div>
	<div id="anatomy-control" class="anatomy-description">
		{% include home/anatomy-mobile.svg %}
		<button class="popup-action" data-panel="anatomy-ui"><img src="{{ "/assets/img/icons/user-interface-link.svg" | relative_url }}">User Interface</button>
		<button class="popup-action" data-panel="anatomy-content"><img src="{{ "/assets/img/icons/content-script-link.svg" | relative_url }}">Content Scripts</button>
		<button class="popup-action" data-panel="anatomy-background"><img src="{{ "/assets/img/icons/background-scripts-link.svg" | relative_url }}">Background Scripts</button>
	</div>
	<p class="manifest show-for-small-only"><img src="{{ "/assets/img/icons/manifest.svg" | relative_url }}">Manifest.json</p>
</div>
<aside class="popup-panel" id="anatomy-ui" markdown="1">

![User Interface](assets/img/icons/user-interface.svg "User Interface")

#### User Interface

Add toolbar buttons, menu choices, and—only in Firefox—sidebars to display additional content. Manage tab behavior and create pop-up windows that respond to user events. 

<button class="close"></button>
</aside>
<aside class="popup-panel" id="anatomy-content" markdown="1">

![Content Scripts](assets/img/icons/content-script.svg "Content Scripts")

#### Content Scripts

Change webpage content. Remove ads, highlight key words, and reformat elements for readability.

<button class="close"></button>
</aside>
<aside class="popup-panel" id="anatomy-background" markdown="1">

![Background Scripts](assets/img/icons/background-scripts.svg "Background Scripts")

#### Background Scripts

Manage long-term configuration beyond the current tab, and respond to user events such as button clicks and menu selections.

<button class="close"></button>
</aside>

</div>
</div>
</div>
<!-- END: Section Anatomy of an Extension -->