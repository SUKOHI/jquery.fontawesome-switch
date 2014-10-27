jquery.fontawesome-switch
=========================

A jQuery package to manage toggle switches of Font-Awesome.

Requirements
====

jQuery, Font-Awesome

Usage
====

At fisrt set hidden-input-tag(s) like the following.

    <input class="toggle" type="hidden" name="name" value="0">

And then in JavaScript code

**Basic way**

    $('.toggle').FASwitch();

**with Parameters**

	$('.toggle').FASwitch({

		css: {
			icon: 'text-warning', 
			label: 'text-success'
		}, 
		labels: {
			0: 'Off', 
			1: 'On'
		}

	});