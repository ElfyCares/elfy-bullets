[![Build Status](https://travis-ci.org/ElfyCares/elfy-bullets.svg?branch=master)](https://travis-ci.org/ElfyCares/elfy-bullets)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/ElfyCares/elfy-bullets)
# \<elfy-bullets\>

A Polymer 2 element to create a small list of removable items.

![alt text](https://raw.githubusercontent.com/ElfyCares/elfy-bullets/master/demo/demo.png)


## Customize the input element and list tag

```
<elfy-bullets input-value-path="address" value-path="address_short" list-tag="li" list-parent-tag="ul">
  <elfy-address-input slot="input" collapse required="street,postalCode,streetNumber,state,country" add-event="save-tapped" clear-input-on-clear-place>
  </elfy-address-input>
</elfy-bullets>
```
