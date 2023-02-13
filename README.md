# spec

Quick summary on how this tool works

## Overview

First of all, what the hell is nolytics? Well, **nolytics** is a no JavaScript solution for website analytics which I created with the intention of measuring my blog tracking performance. Instead of code event metrics, it uses HTML image fetching directly to track web pages hits. All of the measurement/metrics analytics magic is done on the server side, leaving the client free of cookies and CPU usage.

Nolytics is 100% open-source and self-hosted, and you can setup the whole infrastructure right away with a [one-click script](https://github.com/nolytics/setup)!

## Architecture

System communication is very easy to understand as each system component is bounded to a small group of responsibilities and everything can be perceived as a script. No virtual machines are needed, since the system is designed to run on the edge!

![system communication diagram](...)

## Features