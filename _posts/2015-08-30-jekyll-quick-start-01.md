---
layout: post
title: "Jekyll Quick Start 01"
description: ""
category: quick start 
tags: [lesson]
---
{% include JB/setup %}
{% assign name = "world" %}

<script>
var cars = ["Saab", "Volvo", "BMW"];
</script>


## Output
Simple example:

	Hello {{ name }}
	Hello {{ name | upcase }}
	Hello {{ name | downcase }}
	Hello {{ name | capitalize }}
	Hello world, has {{ name | size }} letters
	Hello {{ 'now' | date: "%Y %h" }}
	Hello {{ 'now' | date: "%F %T" }}
	

##Question:

	如何申明一个数组，百思不得其解 ???