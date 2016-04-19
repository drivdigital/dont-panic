---
layout: chapter
title: Conventions
section: Core
permalink: chapters/conventions/
description: Learn the simple conventions that MaintainableCSS employs to write modules, components and state.
---

	/* Square brackets denote optional parts */
	.<moduleName>[__<componentName>][--<state>] {}

Here are some real examples pertaining to a "search results" module:

	/* module container/root */
	.search-results {}

	/* components of a module */
	.search-results__heading {}

	.search-results__item {}

	/* state: such as AJAX loading */
	.search-results--isloading {}

Each of these class names are semantic. Module, component and state are all delimitted by dashes. Each bit is written in lowerCamelCase.
