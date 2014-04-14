silverstripe-jcrop
==================

# jCrop: Image Cropping for SilverStripe inspired by FocusPoint and jCrop

## Overview

The goal of this module is to provide some control over automatic image cropping in SilverStripe.

**Problem:** SilverStripe crops all images from the centre. If the subject is off-centre, it may be cropped out.

**Solution:** jCrop allows you to select the subject in an image and ensures it is not lost during cropping.

## Requirements

SilverStripe 3.1

## Installation

**Manually:** Download, place the folder in your project root and run a dev/build?flush=1 ( folder name must be "jcrop").


## Usage

**In templates:** Use just like CroppedImage, but use CroppedFocusedImage instead.

**In the CMS:** When you edit an image in the CMS there should be an extra 'jCrop' field. Click on the subject of the image to set the focus area and save the image.

## To Do

 * Override CroppedImage() instead of adding new method
 * ImageMagick support (maybe already works - need to test)
 
## Maintainer contact

office@dany.ba

