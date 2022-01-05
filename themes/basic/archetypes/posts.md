---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
author: "Gordon Watts"
year: "{{ dateFormat "2006" .Date}}"
month: "{{ dateFormat "2006/01" .Date}}"
categories:
- Personal
- My Journey
tags:
- Game Development
- Unity
- Teaching
---

Lorem ipsum dolor sit amet, consectetur adipisicing elit, 
seddo eiusmodtempor incididunt ut labore et dolore magna aliqua.
<!--more-->
Ut enim ad minim veniam, quis nostrud exercitation ullamcolaboris
nisi utaliquip ex ea commodo consequat.