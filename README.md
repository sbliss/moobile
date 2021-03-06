moobile
=======

What this will hopefully become is the following:

* A simple semantic set of HTML5 templates to use for iPhone / iPad UI elements and associated CSS
* Pure CSS3 animations for various transitions
* A miniature build of MooTools
* Simple API for Audio and Video embedding, geolocation & maps API
* Helpers for common application tasks using local storage

Further down the line I would hope to also include:

* More themes / theming support
* A simple iPhone application project, which basically runs a HTML5 site wrapped in a Safari frame
* More complex application functionality (for instance user login / authentication)
* Sample .NET MVC / PHP projects


HTML5 Templates
---------------

Pretty obvious really but nice simple Object Oriented CSS for all common UI elements, such as forms, tabs, menus, lists etc. I would try and recreate a few native apps (like settings, photos, contacts, iTunes) to ensure it works.

Wherever possible I would take advantage of Mobile Safari's HTML5 support particularly with forms. A great way to learn about this!

###Example?

	<form>
		<label>Foo</label>
		<fieldset>
			<div>
				<label></label>
				<input type="text" placeholder="Enter bar here" />
			</div>
		</fieldset>
	</form>

	<div class="list>
		<h2>Foo</h2>
		<ul>
			<li><a href="path/to/file.htm" class="slide in">Bar</a></li>
		</ul>
	</div>


CSS3 Animations
---------------

I would like to make things like cubed page groups, the ability to slide back and along like switching pages in Safari, and the album artwork viewer in iTunes.

I also want a simple way to link pages or panels with these transitions - simple classes and a panel handler in MooTools. Some examples of the classes I'm thinking of:

* fade in
* slide *direction*
* flip round, flip *direction*
* travel (?) *direction(index)* - like in Mobile Safari, going from tab 1 to tab 6


Mini MooTools
-------------

Hopefully we can get a mobile webkit build of MooTools - it would be so tiny. Especially 


More info soon!


