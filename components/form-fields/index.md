---
layout: page
parent: "Components"
title: "Form Fields"
intro: "Form fields are multifaceted components that allow Developers to create application forms with appropriate instructional and validation features."
jump_menu: true
---

<div class="ds-preview">
  <div class="fsa-field">
    <label class="fsa-field__label" for="lorem-1234">Email address <span class="fsa-field__label-desc">Required</span></label>
    <input class="fsa-input fsa-field__item" id="lorem-1234" name="lorem-1234" aria-describedby="lorem-1234-help-1" aria-required="true" type="email" value="">
    <span class="fsa-field__help" id="lorem-1234-help-1">This is how people can contact you</span>
  </div>
</div>

## CSS Class Overview

<table class="fsa-table">
  <thead>
    <th scope="col">Selector</th>
    <th scope="col">Description</th>
  </thead>
  <tbody>
    <tr>
      <th scope="row"><code>fsa-field__label</code></th>
      <td>Provide the standard style and position of the label of the form element</td>
    </tr>
    <tr>
      <th scope="row"><code>fsa-field__label-desc</code></th>
      <td>Paired with <code>fsa-field__label</code>, may be used to indicate Required or Optional fields</td>
    </tr>
    <tr>
      <th scope="row"><code>fsa-field__item</code></th>
      <td>Provides standardized style and position for form elements</td>
    </tr>
    <tr>
      <th scope="row"><code>fsa-field__help</code></th>
      <td>Provides instructional text in a standardized location</td>
    </tr>
    <tr>
      <th scope="row"><code>fsa-field__message</code></th>
      <td>Provides validation and error messaging in standardized location</td>
    </tr>
  </tbody>
</table>

## Variations

Below are the variations and code snippets that can be applied using `class="fsa-field"`.

### Default

```html
<div class="fsa-field">
  <label class="fsa-field__label" for="TheItem2">Label <span class="fsa-field__label-desc">Required</span></label>
  <input class="fsa-input fsa-field__item" id="TheItem2" aria-describedby="lorem-1234-help-2" aria-required="true" name="TheItem2" type="text" value="">
  <span class="fsa-field__help" id="lorem-1234-help-2">Instructional message here</span>
</div>
```
<div class="ds-preview">
  <div class="fsa-field">
    <label class="fsa-field__label" for="TheItem2">Label <span class="fsa-field__label-desc">Required</span></label>
    <input class="fsa-input fsa-field__item" id="TheItem2" aria-describedby="lorem-1234-help-2" aria-required="true" name="TheItem2" type="text" value="">
    <span class="fsa-field__help" id="lorem-1234-help-2">Instructional message here</span>
  </div>
</div>

### Short

```html
<div class="fsa-field">
  <label class="fsa-field__label" for="TheItem3">Label <span class="fsa-field__label-desc">Required</span></label>
  <input class="fsa-input fsa-field__item fsa-field__item--short" id="TheItem3" aria-describedby="lorem-1234-help-3" aria-required="true" name="TheItem3" type="text" value="">
  <span class="fsa-field__help" id="lorem-1234-help-3">Instructional message here</span>
</div>
```
<div class="ds-preview">
  <div class="fsa-field">
    <label class="fsa-field__label" for="TheItem3">Label <span class="fsa-field__label-desc">Required</span></label>
    <input class="fsa-input fsa-field__item fsa-field__item--short" id="TheItem3" aria-describedby="lorem-1234-help-3" aria-required="true" name="TheItem3" type="text" value="">
    <span class="fsa-field__help" id="lorem-1234-help-3">Instructional message here</span>
  </div>
</div>

### Medium

```html
<div class="fsa-field">
  <label class="fsa-field__label" for="TheItem4">Label <span class="fsa-field__label-desc">Required</span></label>
  <input class="fsa-input fsa-field__item fsa-field__item--medium" id="TheItem4" aria-describedby="lorem-1234-help-4" aria-required="true" name="TheItem4" type="text" value="">
  <span class="fsa-field__help" id="lorem-1234-help-4">Instructional message here</span>
</div>
```
<div class="ds-preview">
  <div class="fsa-field">
    <label class="fsa-field__label" for="TheItem4">Label <span class="fsa-field__label-desc">Required</span></label>
    <input class="fsa-input fsa-field__item fsa-field__item--medium" id="TheItem4" aria-describedby="lorem-1234-help-4" aria-required="true" name="TheItem4" type="text" value="">
    <span class="fsa-field__help" id="lorem-1234-help-4">Instructional message here</span>
  </div>
</div>

### Full Width

```html
<div class="fsa-field--block">
  <label class="fsa-field__label" for="TheItem5">Label <span class="fsa-field__label-desc">Required</span></label>
  <input class="fsa-input fsa-field__item" id="TheItem5" aria-describedby="lorem-1234-help-5" aria-required="true" name="TheItem5" type="text" value="">
  <span class="fsa-field__help" id="lorem-1234-help-5">Instructional message here</span>
</div>
```
<div class="ds-preview">
  <div class="fsa-field--block">
    <label class="fsa-field__label" for="TheItem5">Label <span class="fsa-field__label-desc">Required</span></label>
    <input class="fsa-input fsa-field__item" id="TheItem5" aria-describedby="lorem-1234-help-5" aria-required="true" name="TheItem5" type="text" value="">
    <span class="fsa-field__help" id="lorem-1234-help-5">Instructional message here</span>
  </div>
</div>

## States

### Error

```html
<div class="fsa-field fsa-field--error">
  <label class="fsa-field__label" for="TheItem6">Label <span class="fsa-field__label-desc">Required</span></label>
  <input class="fsa-input fsa-field__item fsa-input--error" id="TheItem6" aria-describedby="lorem-1234-help-6 lorem-1234-message-6" aria-required="true" name="TheItem6" type="text" value="">
  <span class="fsa-field__help" id="lorem-1234-help-6">Instructional message here</span>
  <span class="fsa-field__message" id="lorem-1234-message-6" role="alert">Helpful error message here</span>
</div>
```
<div class="ds-preview">
  <div class="fsa-field fsa-field--error">
    <label class="fsa-field__label" for="TheItem6">Label <span class="fsa-field__label-desc">Required</span></label>
    <input class="fsa-input fsa-field__item fsa-input--error" id="TheItem6" aria-describedby="lorem-1234-help-6 lorem-1234-message-6" aria-required="true" name="TheItem6" type="text" value="">
    <span class="fsa-field__help" id="lorem-1234-help-6">Instructional message here</span>
    <span class="fsa-field__message" id="lorem-1234-message-6" role="alert">Helpful error message here</span>
  </div>
</div>

### Positive

```html
<div class="fsa-field">
  <label class="fsa-field__label" for="TheItem7">Label</label>
  <input class="fsa-input fsa-field__item fsa-input--positive" id="TheItem7" aria-describedby="lorem-1234-help-7" name="TheItem7" type="text" value="Lorem ipsum">
  <span class="fsa-field__help" id="lorem-1234-help-7">Instructional message here</span>
</div>
```
<div class="ds-preview">
  <div class="fsa-field">
    <label class="fsa-field__label" for="TheItem7">Label</label>
    <input class="fsa-input fsa-field__item fsa-input--positive" id="TheItem7" aria-describedby="lorem-1234-help-7" name="TheItem7" type="text" value="Lorem ipsum">
    <span class="fsa-field__help" id="lorem-1234-help-7">Instructional message here</span>
  </div>
</div>

### Error - specific field in row

```html
<div class="fsa-field fsa-field--columns fsa-field--error">
  <div class="fsa-grid">
    <div class="fsa-grid__1 fsa-grid__2/3@m">
      <div class="fsa-field__column">
        <label class="fsa-field__label" for="city">City</label>
        <input class="fsa-input fsa-field__item" id="city" name="city" type="text" value="Carpinteria">
      </div>
    </div>
    <div class="fsa-grid__1 fsa-grid__1/3@m">
      <div class="fsa-field__column">
        <label class="fsa-field__label" for="st">State</label>
        <select class="fsa-select fsa-select--error fsa-field__item" aria-describedby="st--message" id="st" name="st">
          <option value="" selected></option>
          <option value="Alabama">AL</option>
          <option value="Alaska">AK</option>
          <option value="Arizona">AZ</option>
          <option value="Arkansas">AR</option>
        </select>
        <span class="fsa-field__message" id="st--message" role="alert">State is required</span>
      </div>
    </div>
  </div>
</div>
```
<div class="ds-preview">
  <div class="fsa-field fsa-field--columns fsa-field--error">
    <div class="fsa-grid">
      <div class="fsa-grid__1 fsa-grid__2/3@m">
        <div class="fsa-field__column">
          <label class="fsa-field__label" for="city">City</label>
          <input class="fsa-input fsa-field__item" id="city" name="city" type="text" value="Carpinteria">
        </div>
      </div>
      <div class="fsa-grid__1 fsa-grid__1/3@m">
        <div class="fsa-field__column">
          <label class="fsa-field__label" for="st">State</label>
          <select class="fsa-select fsa-select--error fsa-field__item" aria-describedby="st--message" id="st" name="st">
            <option value="" selected></option>
            <option value="Alabama">AL</option>
            <option value="Alaska">AK</option>
            <option value="Arizona">AZ</option>
            <option value="Arkansas">AR</option>
          </select>
          <span class="fsa-field__message" id="st--message" role="alert">State is required</span>
        </div>
      </div>
    </div>
  </div>
</div>

### Field Columns

By using `fsa-field--columns` paired with [Grids]({{ site.baseurl }}visual-style/grid/), you can define a consistant column structure for larger screens, while they will stack on smaller screens (e.g. handheld devices).

```html
<div class="fsa-field fsa-field--block fsa-field--columns">
  <div class="fsa-grid">
    <div class="fsa-grid__1 fsa-grid__3/12@s">
      <div class="fsa-field__column">
        <label class="fsa-field__label" for="lorem-555s">Label 1A</label>
        <input class="fsa-input fsa-field__item" id="lorem-555s" name="lorem-555s" type="text" value="">
      </div>
    </div>
    <div class="fsa-grid__1 fsa-grid__3/12@s">
      <div class="fsa-field__column">
        <label class="fsa-field__label" for="lorem-3344">Label 2A</label>
        <input class="fsa-input fsa-field__item" id="lorem-3344" name="lorem-3344" type="text" value="">
      </div>
    </div>
    <div class="fsa-grid__1 fsa-grid__6/12@s">
      <div class="fsa-field__column">
        <label class="fsa-field__label" for="lorem-9915">Label 3A</label>
        <select class="fsa-select fsa-field__item" id="lorem-9915" name="lorem-9915">
          <option value="" selected>- Select a lorem -</option>
          <option value="Ipsum">Ipsum</option>
          <option value="Dolor">Dolor</option>
          <option value="Sit">Sit</option>
          <option value="Amet">Amet</option>
          <option value="Consecutar">Consecutar</option>
        </select>
      </div>
    </div>
  </div>
</div>
<div class="fsa-field fsa-field--block fsa-field--columns">
  <div class="fsa-grid">
    <div class="fsa-grid__1 fsa-grid__3/12@s">
      <div class="fsa-field__column">
        <label class="fsa-field__label" for="lorem-6459">Label 1B</label>
        <input class="fsa-input fsa-field__item" id="lorem-6459" name="lorem-6459" type="text" value="">
      </div>
    </div>
    <div class="fsa-grid__1 fsa-grid__3/12@s">
      <div class="fsa-field__column">
        <label class="fsa-field__label" for="lorem-6543">Label 2B</label>
        <input class="fsa-input fsa-field__item" id="lorem-6543" name="lorem-6543" type="text" value="">
      </div>
    </div>
    <div class="fsa-grid__1 fsa-grid__6/12@s">
      <div class="fsa-field__column">
        <label class="fsa-field__label" for="lorem-0892">Label 3B</label>
        <select class="fsa-select fsa-field__item" id="lorem-0892" name="lorem-0892">
          <option value="" selected>- Select a lorem -</option>
          <option value="Ipsum">Ipsum</option>
          <option value="Dolor">Dolor</option>
          <option value="Sit">Sit</option>
          <option value="Amet">Amet</option>
          <option value="Consecutar">Consecutar</option>
        </select>
      </div>
    </div>
  </div>
</div>
```
<div class="ds-preview">
  <div class="fsa-field fsa-field--block fsa-field--columns">
    <div class="fsa-grid">
      <div class="fsa-grid__1 fsa-grid__3/12@s">
        <div class="fsa-field__column">
          <label class="fsa-field__label" for="lorem-555s">Label 1A</label>
          <input class="fsa-input fsa-field__item" id="lorem-555s" name="lorem-555s" type="text" value="">
        </div>
      </div>
      <div class="fsa-grid__1 fsa-grid__3/12@s">
        <div class="fsa-field__column">
          <label class="fsa-field__label" for="lorem-3344">Label 2A</label>
          <input class="fsa-input fsa-field__item" id="lorem-3344" name="lorem-3344" type="text" value="">
        </div>
      </div>
      <div class="fsa-grid__1 fsa-grid__6/12@s">
        <div class="fsa-field__column">
          <label class="fsa-field__label" for="lorem-9915">Label 3A</label>
          <select class="fsa-select fsa-field__item" id="lorem-9915" name="lorem-9915">
            <option value="" selected>- Select a lorem -</option>
            <option value="Ipsum">Ipsum</option>
            <option value="Dolor">Dolor</option>
            <option value="Sit">Sit</option>
            <option value="Amet">Amet</option>
            <option value="Consecutar">Consecutar</option>
          </select>
        </div>
      </div>
    </div>
  </div>
  <div class="fsa-field fsa-field--block fsa-field--columns">
    <div class="fsa-grid">
      <div class="fsa-grid__1 fsa-grid__3/12@s">
        <div class="fsa-field__column">
          <label class="fsa-field__label" for="lorem-6459">Label 1B</label>
          <input class="fsa-input fsa-field__item" id="lorem-6459" name="lorem-6459" type="text" value="">
        </div>
      </div>
      <div class="fsa-grid__1 fsa-grid__3/12@s">
        <div class="fsa-field__column">
          <label class="fsa-field__label" for="lorem-6543">Label 2B</label>
          <input class="fsa-input fsa-field__item" id="lorem-6543" name="lorem-6543" type="text" value="">
        </div>
      </div>
      <div class="fsa-grid__1 fsa-grid__6/12@s">
        <div class="fsa-field__column">
          <label class="fsa-field__label" for="lorem-0892">Label 3B</label>
          <select class="fsa-select fsa-field__item" id="lorem-0892" name="lorem-0892">
            <option value="" selected>- Select a lorem -</option>
            <option value="Ipsum">Ipsum</option>
            <option value="Dolor">Dolor</option>
            <option value="Sit">Sit</option>
            <option value="Amet">Amet</option>
            <option value="Consecutar">Consecutar</option>
          </select>
        </div>
      </div>
    </div>
  </div>
  <p>(Resize browser or view on handheld devices to view responsive behavior.)</p>
</div>

### Field Columns - with error of specific field

```html
<div class="fsa-field fsa-field--block fsa-field--columns fsa-field--error">
  <div class="fsa-grid">
    <div class="fsa-grid__1 fsa-grid__3/12@s">
      <div class="fsa-field__column">
        <label class="fsa-field__label" for="lorem-4705">Label 1A</label>
        <input class="fsa-input fsa-field__item" id="lorem-4705" name="lorem-4705" type="text" value="">
      </div>
    </div>
    <div class="fsa-grid__1 fsa-grid__3/12@s">
      <div class="fsa-field__column">
        <label class="fsa-field__label" for="lorem-3294">Label 2A</label>
        <input class="fsa-input fsa-input--error fsa-field__item" aria-describedby="lorem-3294--error-message" id="lorem-3294" name="lorem-3294" type="text" value="">
        <span class="fsa-field__message" id="lorem-3294--error-message" role="alert">Helpful error message</span>
      </div>
    </div>
    <div class="fsa-grid__1 fsa-grid__6/12@s">
      <div class="fsa-field__column">
        <label class="fsa-field__label" for="lorem-9235">Label 3A</label>
        <select class="fsa-select fsa-field__item" id="lorem-9235" name="lorem-9235">
          <option value="" selected>- Select a lorem -</option>
          <option value="Ipsum">Ipsum</option>
          <option value="Dolor">Dolor</option>
          <option value="Sit">Sit</option>
          <option value="Amet">Amet</option>
          <option value="Consecutar">Consecutar</option>
        </select>
      </div>
    </div>
  </div>
</div>
<div class="fsa-field fsa-field--block fsa-field--columns">
  <div class="fsa-grid">
    <div class="fsa-grid__1 fsa-grid__3/12@s">
      <div class="fsa-field__column">
        <label class="fsa-field__label" for="lorem-6556">Label 1B</label>
        <input class="fsa-input fsa-field__item" id="lorem-6556" name="lorem-6556" type="text" value="">
      </div>
    </div>
    <div class="fsa-grid__1 fsa-grid__3/12@s">
      <div class="fsa-field__column">
        <label class="fsa-field__label" for="lorem-3343">Label 2B</label>
        <input class="fsa-input fsa-field__item" id="lorem-3343" name="lorem-3343" type="text" value="">
      </div>
    </div>
    <div class="fsa-grid__1 fsa-grid__6/12@s">
      <div class="fsa-field__column">
        <label class="fsa-field__label" for="lorem-0222">Label 3B</label>
        <select class="fsa-select fsa-field__item" id="lorem-0222" name="lorem-0222">
          <option value="" selected>- Select a lorem -</option>
          <option value="Ipsum">Ipsum</option>
          <option value="Dolor">Dolor</option>
          <option value="Sit">Sit</option>
          <option value="Amet">Amet</option>
          <option value="Consecutar">Consecutar</option>
        </select>
      </div>
    </div>
  </div>
</div>
```
<div class="ds-preview">
  <div class="fsa-field fsa-field--block fsa-field--columns fsa-field--error">
    <div class="fsa-grid">
      <div class="fsa-grid__1 fsa-grid__3/12@s">
        <div class="fsa-field__column">
          <label class="fsa-field__label" for="lorem-4705">Label 1A</label>
          <input class="fsa-input fsa-field__item" id="lorem-4705" name="lorem-4705" type="text" value="">
        </div>
      </div>
      <div class="fsa-grid__1 fsa-grid__3/12@s">
        <div class="fsa-field__column">
          <label class="fsa-field__label" for="lorem-3294">Label 2A</label>
          <input class="fsa-input fsa-input--error fsa-field__item" aria-describedby="lorem-3294--error-message" id="lorem-3294" name="lorem-3294" type="text" value="">
          <span class="fsa-field__message" id="lorem-3294--error-message" role="alert">Helpful error message</span>
        </div>
      </div>
      <div class="fsa-grid__1 fsa-grid__6/12@s">
        <div class="fsa-field__column">
          <label class="fsa-field__label" for="lorem-9235">Label 3A</label>
          <select class="fsa-select fsa-field__item" id="lorem-9235" name="lorem-9235">
            <option value="" selected>- Select a lorem -</option>
            <option value="Ipsum">Ipsum</option>
            <option value="Dolor">Dolor</option>
            <option value="Sit">Sit</option>
            <option value="Amet">Amet</option>
            <option value="Consecutar">Consecutar</option>
          </select>
        </div>
      </div>
    </div>
  </div>
  <div class="fsa-field fsa-field--block fsa-field--columns">
    <div class="fsa-grid">
      <div class="fsa-grid__1 fsa-grid__3/12@s">
        <div class="fsa-field__column">
          <label class="fsa-field__label" for="lorem-6556">Label 1B</label>
          <input class="fsa-input fsa-field__item" id="lorem-6556" name="lorem-6556" type="text" value="">
        </div>
      </div>
      <div class="fsa-grid__1 fsa-grid__3/12@s">
        <div class="fsa-field__column">
          <label class="fsa-field__label" for="lorem-3343">Label 2B</label>
          <input class="fsa-input fsa-field__item" id="lorem-3343" name="lorem-3343" type="text" value="">
        </div>
      </div>
      <div class="fsa-grid__1 fsa-grid__6/12@s">
        <div class="fsa-field__column">
          <label class="fsa-field__label" for="lorem-0222">Label 3B</label>
          <select class="fsa-select fsa-field__item" id="lorem-0222" name="lorem-0222">
            <option value="" selected>- Select a lorem -</option>
            <option value="Ipsum">Ipsum</option>
            <option value="Dolor">Dolor</option>
            <option value="Sit">Sit</option>
            <option value="Amet">Amet</option>
            <option value="Consecutar">Consecutar</option>
          </select>
        </div>
      </div>
    </div>
  </div>
</div>

### Checkbox Field

```html
<div class="fsa-field">
  <label class="fsa-field__label" id="unique-id-lorem--1234">Pies We Like</label>
  <ul class="fsa-form-list" aria-labelledby="unique-id-lorem--1234">
    <li>
      <input class="fsa-checkbox" id="apple" type="checkbox" name="pie" checked="">
      <label for="apple">Apple</label>
    </li>
    <li>
      <input class="fsa-checkbox" id="key-lime" type="checkbox" name="pie">
      <label for="key-lime">Key Lime</label>
    </li>
    <li>
      <input class="fsa-checkbox" id="pumpkin" type="checkbox" name="pie">
      <label for="pumpkin">Pumpkin</label>
    </li>
  </ul>
</div>
```
<div class="ds-preview">
  <div class="fsa-field">
    <label class="fsa-field__label" id="unique-id-lorem--1234">Pies We Like</label>
    <ul class="fsa-form-list" aria-labelledby="unique-id-lorem--1234">
      <li>
        <input class="fsa-checkbox" id="apple" type="checkbox" name="pie" checked="">
        <label for="apple">Apple</label>
      </li>
      <li>
        <input class="fsa-checkbox" id="key-lime" type="checkbox" name="pie">
        <label for="key-lime">Key Lime</label>
      </li>
      <li>
        <input class="fsa-checkbox" id="pumpkin" type="checkbox" name="pie">
        <label for="pumpkin">Pumpkin</label>
      </li>
    </ul>
  </div>
</div>

### Radio Field

```html
<div class="fsa-field">
  <label class="fsa-field__label" id="lorem-radio-field-1">Your Favorite Pie</label>
  <ul class="fsa-form-list" aria-labelledby="lorem-radio-field-1">
    <li>
      <input class="fsa-radio" id="apple-radio" type="radio" name="fav-pie">
      <label for="apple-radio">Apple</label>
    </li>
    <li>
      <input class="fsa-radio" id="key-lime-radio" type="radio" name="fav-pie">
      <label for="key-lime-radio">Key Lime</label>
    </li>
    <li>
      <input class="fsa-radio" id="pumpkin-radio" type="radio" name="fav-pie">
      <label for="pumpkin-radio">Pumpkin</label>
    </li>
    <li>
      <input class="fsa-radio" id="none-radio" type="radio" name="fav-pie" checked>
      <label for="none-radio">None of the above</label>
    </li>
  </ul>
</div>
```
<div class="ds-preview">
  <div class="fsa-field">
    <label class="fsa-field__label" id="lorem-radio-field-1">Your Favorite Pie</label>
    <ul class="fsa-form-list" aria-labelledby="lorem-radio-field-1">
      <li>
        <input class="fsa-radio" id="apple-radio" type="radio" name="fav-pie">
        <label for="apple-radio">Apple</label>
      </li>
      <li>
        <input class="fsa-radio" id="key-lime-radio" type="radio" name="fav-pie">
        <label for="key-lime-radio">Key Lime</label>
      </li>
      <li>
        <input class="fsa-radio" id="pumpkin-radio" type="radio" name="fav-pie">
        <label for="pumpkin-radio">Pumpkin</label>
      </li>
      <li>
        <input class="fsa-radio" id="none-radio" type="radio" name="fav-pie" checked>
        <label for="none-radio">None of the above</label>
      </li>
    </ul>
  </div>
</div>

### Radio Field with Error

```html
<div class="fsa-field fsa-field--error">
  <label class="fsa-field__label" id="lorem-radio-field-2">Your Favorite Pie</label>
  <ul class="fsa-form-list" aria-labelledby="lorem-radio-field-2" aria-describedby="pie-err--message">
    <li>
      <input class="fsa-radio" id="apple-radio-err" type="radio" name="fav-pie-err" checked>
      <label for="apple-radio-err">Apple</label>
    </li>
    <li>
      <input class="fsa-radio" id="key-lime-radio-err" type="radio" name="fav-pie-err">
      <label for="key-lime-radio-err">Key Lime</label>
    </li>
    <li>
      <input class="fsa-radio" id="pumpkin-radio-err" type="radio" name="fav-pie-err">
      <label for="pumpkin-radio-err">Pumpkin</label>
    </li>
    <li>
      <input class="fsa-radio" id="none-radio-err" type="radio" name="fav-pie-err">
      <label for="none-radio-err">None of the above</label>
    </li>
  </ul>
  <span class="fsa-field__message" id="pie-err--message" role="alert">Helpful error message</span>
</div>
```
<div class="ds-preview">
  <div class="fsa-field fsa-field--error">
    <label class="fsa-field__label" id="lorem-radio-field-2">Your Favorite Pie</label>
    <ul class="fsa-form-list" aria-labelledby="lorem-radio-field-2" aria-describedby="pie-err--message">
      <li>
        <input class="fsa-radio" id="apple-radio-err" type="radio" name="fav-pie-err" checked>
        <label for="apple-radio-err">Apple</label>
      </li>
      <li>
        <input class="fsa-radio" id="key-lime-radio-err" type="radio" name="fav-pie-err">
        <label for="key-lime-radio-err">Key Lime</label>
      </li>
      <li>
        <input class="fsa-radio" id="pumpkin-radio-err" type="radio" name="fav-pie-err">
        <label for="pumpkin-radio-err">Pumpkin</label>
      </li>
      <li>
        <input class="fsa-radio" id="none-radio-err" type="radio" name="fav-pie-err">
        <label for="none-radio-err">None of the above</label>
      </li>
    </ul>
    <span class="fsa-field__message" id="pie-err--message" role="alert">Helpful error message</span>
  </div>
</div>

## Accessibility

Always refer to the [Accessibility Forms Guide]({{ site.baseurl }}guides/accessibility/forms) for overall guidance.

If you customize the text inputs, ensure they continue to meet the the accessibility requirements that apply to all form controls.

* Do not use the `placeholder` attribute as the sole label for accessibility reasons. Form components must have an associated `<label>` with matching `for` attribute. Additionally, most browsers’ default rendering of placeholder text does not provide a high enough contrast ratio to sufficiently serve as the sole label.
* Avoid breaking numbers with distinct sections (such as phone numbers, Social Security Numbers, or credit card numbers) into separate input fields. For example, use one input for phone number, not three (one for area code, one for local code, and one for number). Each field needs to be labeled for a screen reader and the labels for fields broken into segments are often not meaningful.

## General Guidance

* The length of the text input provides a hint to users as to how much text to write. Do not require users to write paragraphs of text into a single-line input box; use a [textarea]({{ site.baseurl }}components/textarea/) instead.
* Text inputs are among the easiest type of input for desktop users but are more difficult for mobile users.
* Consider the type of content a user may enter to aid mobile device entry; mobile devices typically surface a keyboard UI attuned to the type. For example, `type="tel"` will surface a [phone keyboard](http://html5doctor.com/html5-forms-input-types/#input-tel).
* Only show error validation messages or styling after a user has interacted with a particular field; avoid significantly updating styles while a user is actively entering input.
* Do not use the `placeholder` attribute in place of a `<label>` element. Its purposes is different: the standard `<label>` describes the role of the form element; that is, it indicates what kind of information is expected. The `placeholder` attribute is typically a hint about the format the content should take. There are cases in which the placeholder attribute is not displayed to the user (e.g. when input field has a value), so the form must be understandable without it.
