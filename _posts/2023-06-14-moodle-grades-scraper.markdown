---
layout:     post
title:      "Moodle Grades Scraper"
date:       2023-06-14 12:00:00
author:     "L'Usine Logicielle"
header-img: "img/post-bg-2015.jpg"
tags:
    - Python
    - Docker
    - MariaDB
---

The Moodle Grades Scraper project is a collaborative initiative between me and my classmate Lucas Perfeito. Using web scraping on our school’s Moodle website, we’ve set up an alert system, via Discord or by e-mail, to inform our classmates when a new note is added or modified. The script used for this project is hosted on our own servers.

This project is designed with Python 🐍 for the script part, Docker 🐳 for the deployement part and MariaDB for the storage part. Alerts can be send by e-mail or with Discord notifications (via a webhook), as shown in the following images.