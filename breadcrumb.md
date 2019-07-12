---
title: Example: Breadcrumb
categories: navigation
tags: links lists location
---
# {{page.title}}

Tags: {{page.tags}}

> UX team provides description of pattern purpose and behavior (browse path, hierarchical, other)

## Example
> UX team provides illustratoin of breadcrumb for easy identification

## Usage
> UX team outlines guidelines for component use and related concerns.

 * Use to indicate the current site hierarchy location to users.
 * more...

## Accessibility Guideline
Breadcrumbs are custom components that need extra ARIA semantics to be accessible.

* Use native HTML ```nav``` element to contain the breadcrumb, it has an implicit navigation role.
* Add an ```aria-label="breadcrumb"``` attribute to describe the type of navigation.
* IF the current location in the breadcrumb is a link, then identify the link state using with ```aria-current="page"``` attribute.
* Ensure pages use a consistent navigation structure

<details>
  <summary>References</summary>
  <ul>
    <li><a href="https://www.w3.org/WAI/WCAG21/quickref/?currentsidebar=%23col_overview#consistent-navigation" target="_blank">WCAG 2.1 3.2.3 Consistent Navigation</a> - Navigational mechanisms that are repeated on multiple Web pages within a set of Web pages occur in the same relative order each time they are repeated, unless a change is initiated by the user. (Level AA)
    </li>
    <li><a href="https://www.w3.org/WAI/WCAG21/quickref/?currentsidebar=%23col_overview#consistent-navigation" target="_blank">WCAG 2.1 3.2.4 Consistent Identification</a> - Components that have the same functionality within a set of Web pages are identified consistently. (Level AA)
    </li>
    <li><a href="https://www.w3.org/WAI/WCAG20/quickref/?showtechniques=131#navigation-mechanisms-location" target="_blank" data-la-initvishidden="true">WCAG 2.1 - 2.4.8 Location</a> - Information about the user's location within a set of Web pages is available. (Level AAA)
    </li>
    <li><a href="https://www.w3.org/TR/wai-aria-practices-1.1/#breadcrumb">WAI-ARIA Authoring Practices 1.1 - 3.4 Breadcrumb</a></li>
  </ul>
</details>


## Interactive Demo
> Embed or link to working code sample

## Code Sample
> Reference to your framework API docs or library.

OR

```
<nav aria-label="breadcrumb">
  Developer's sample code goes here.
</nav>
```
