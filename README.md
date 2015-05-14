# &lt;gaia-list&gt; [![](https://travis-ci.org/gaia-components/gaia-list.svg)](https://travis-ci.org/gaia-components/gaia-list) [![devDependency Status](https://david-dm.org/gaia-components/gaia-list/dev-status.svg)](https://david-dm.org/gaia-components/gaia-list#info=devDependencies)


## Installation

```bash
$ bower install gaia-components/gaia-list
```


## Examples

- [Example](http://gaia-components.github.io/gaia-list/)


## Usage

All gaia-list item should be wrap in the `<li>` tag.

gaia-list provide semantic based declaration and class based declaration.

You can use `<hx>` as main text, use `p` or `small` as description.
Or you can add `gaia-item-title` class to denote the element is the main text, add `gaia-item-desc` class to denote the element is the description.

### Settings style list

Semantic

```
<gaia-list>
  <li>
    <a>
      <i data-icon="brightness"></i>
      <h3 flex>Menu 1</h3>
      <i data-icon="forward-light"></i>
      </a>
  <li>
</gaia-list>
```

class based

```
<gaia-list>
  <li>
    <a>
      <i data-icon="brightness"></i>
      <div class="gaia-item-title">Menu 1</h3>
      <i data-icon="forward-light"></i>
      </a>
  <li>
</gaia-list>
```


List with switch and divider

```
<gaia-list>
  <li>
    <a>
      <label flex flexbox for="wifi-switch">
        <i data-icon="wifi-4"></i>
        <h3>Wifi</h3>
      </label>
      <gaia-switch id="wifi-switch" class="divided"></gaia-switch>
    </a>
  </li>
</gaia-list>
```

### Contacts style list

```
<gaia-list>
  <li>
    <a>
      <div>
        <h3>Noah Green</h3>
        <p>Atsara Kitchens</p>
        <div class="face"></div>
      </div>
    </a>
  </li>
</gaia-list>
```

### Email style list (with time stamp)

```
<gaia-list>
  <li>
    <a class="unread">
      <div>
        <h3>Will Gordan</h3>
        <p>Send photos please!</p>
        <p>You're the best, thank you so much for all</p>
        <time>11:30AM</time>
      </div>
    </a>
  </li>
  <li>
    <a>
      <div>
        <h3>Michael Stanford</h3>
        <p>You might like this or not?</p>
        <p>Great find, I definitely check with Brian if</p>
        <time>11:30AM</time>
      </div>
    </a>
  </li>
</gaia-list>
```

### flexbox

Defines the element as a `display: flex`.

### flex

Expands element to fill available space `flex: 1`


## Lint check

Run lint check with command:

`$ npm run lint`
