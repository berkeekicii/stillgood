# StillGood

An AI-powered mobile marketplace concept that connects farms and consumers, so that produce that looks imperfect but is still good does not go to waste.

**Live demo:** https://berkeekicii.github.io/stillgood/

## Background

StillGood is one of the project ideas developed during the Erasmus+ KA152 Youth Exchange "Young Ambassadors of Ecological Agriculture" in Mersin, Türkiye. Millions of tons of fresh produce never reach the grocery store just because it does not look perfect. The idea was to take a whiteboard concept to a playable UI prototype that shows how technology could help with agricultural waste management.

## The idea

**1. Scan in the garden.** Growers scan harvested fruits and vegetables with their smartphone camera.

**2. Grade with machine learning.** A model evaluates surface blemishes, shape and freshness.

**3. Route for maximum value.** Slightly bruised or odd-shaped produce is listed on a discounted marketplace, so consumers get fresh food at lower prices and farmers keep their revenue. Spoiled produce is separated and sent to composting and organic fertilizer production. Premium produce goes to the regular retail shelf.

## What this prototype does

This repository is a single-page, clickable prototype that runs in the browser inside a phone-shaped frame.

**Login screen.** Choose between a Producer view (garden) and a Consumer view (market).

**Producer view.** Pick a crop (apple, carrot, tomato, lemon, pepper, pear), run a scan animation and see the grade, confidence and surface check. Depending on the grade you can send the crop to the discount market, to a local stand or shelf, or turn it into bio-fertilizer.

**Consumer view.** Browse the marketplace, filter by Fruit, Vegetables or Fertilizer, add items to the basket and complete a one-click checkout. Items you list as a producer show up in the marketplace.

**History.** A log of recent actions, such as items marketed, fertilized or purchased.

## Important note

The scanning is simulated. Each crop has a predefined grade and confidence value, and no real machine learning model runs in this prototype. It demonstrates the intended user flow, not a working detector. For a real image-based defect detector from my other work, see [capsule-detector-yolov8](https://github.com/berkeekicii/capsule-detector-yolov8).

## Run locally

There is nothing to install. Download or clone the repository and open `index.html` in a browser.

## Built with

HTML, CSS and vanilla JavaScript in a single file, with the Inter font from Google Fonts.
