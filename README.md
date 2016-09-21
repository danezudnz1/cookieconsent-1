# Cookie Consent [Deprecated]

Javascript plugin allowing a website to comply with the EU cookie law.

## Deprecation
The web has moved on substantually since this was originally created, both in terms of technology and in terms of cookie laws.

This project was originally written heavily in jQuery and isn't particularly performant, something that is becoming more and more important in todays web.

We've since released a [new version](https://github.com/insites/cookieconsent) that is built more up to modern web standards.

## Legacy Readme

### Features

* Free to use and modify
* Only show to EU visitors
* Opt in once for all sites
* Implied or explicit consent
* Works with [do not track](http://donottrack.us/)

### Integration

Refer to the [Cookie Consent website](http://sitebeam.net/cookieconsent/) for detailed integration documentation and
 our simple [configuration wizard](http://sitebeam.net/cookieconsent/code/) to see what can be customized.

### Basic usage

    <link rel="stylesheet" type="text/css" href="cookieconsent.css"/>
    <script type="text/javascript" src="cookieconsent.js"></script>

    <script type="text/javascript">
    // <![CDATA[
    cc.initialise({
    	cookies: {
    		social: {},
    		analytics: {},
    		advertising: {},
    		necessary: {}
    	},
    	settings: {
    		consenttype: "implicit"
    	}
    });
    // ]]>
    </script>

### Credits
Created by [Silktide](https://silktide.com).
