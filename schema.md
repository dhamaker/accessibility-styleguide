---
title: Accessibility Style Guide Taxonomy
layout: page
---
# {{page.title}}
## General Principles
* __Design for Web Standards__ - Native HTML is very accessible. Don't break it. HTML has semantic roles and attributes that support accessibility with only basic knowledge of HTML.
* __Design for progressive enhancement__.  Look at basic HTML first.  Next, Enhance the  basic elements for your experience.  Finally, carefully evaluate custom component as a last resort.
* __Responsive Use__ - One document. Multiple devices, multiple inputs, multiple presentations.  This means presntation to desktop, mobile, tablet, screen reader, and braile; plus print, screen, audio; humans and machines crawlers and screenscrappers.
* __Use Accessible Tools__ Use Know the capabilities of your authoring tools.  Use third-party libraries and applications that are built for Accessibility.  Some tools will generate accessible content with no extra work on your part.  Other's will never generate accessible content.  And, others will only do so with custom development.
* __Consistency__.  Apply your designs and coding conventions consistently.

## By General Design
* Consistency
* Contrast
* Color
* Typography
* Content Structure
* Wayfinding and Signage
  * Titles
  * Actions
  * navigation
  * focus

## Custom components (+ARIA)
Creates new features with custom semantics and behaviors.  May changes the native behavior of elements.  Require additional ARIA tag design for accessibility.
  * Accordion
  * Activity messaging
    * Button with progress messaging
    * Loading spinners
  * Input drag and drop
  * Dialog, modal
  * Panels 
  * Carousel
  
## Enhanced components (+ARIA)
Extends native HTML semantics and behaviors to enhance experience. Require additional ARIA tag design for accessibility.
* Tabs
* Forms 
  * Radio selections with customized graphics
  * Checkboxs
  * Input + instructions, descriptions
  * Input + message, character count
  * Input + message, validation 
  * Input with button actions
    * date input
* Navigation
  * Breadcrumb
  * Step or Process Flow
    
  
## Standard elements

* Structure
  * Headings
  * Lists
  * Tables
* Layout
  * Articles
  * Sections
  * Asides
  * Global
    * headers
    * navigation
    * footers
* Forms
  * Radio (stylized,)
* Links
* Interactive Content
  * Details (expand/collapse)
  *
* Media
* Images


