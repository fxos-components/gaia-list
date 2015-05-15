# &lt;gaia-list&gt; [![](https://travis-ci.org/gaia-components/gaia-list.svg)](https://travis-ci.org/gaia-components/gaia-list) [![devDependency Status](https://david-dm.org/gaia-components/gaia-list/dev-status.svg)](https://david-dm.org/gaia-components/gaia-list#info=devDependencies)

## Installation

```bash
$ bower install gaia-components/gaia-list
```

## Examples

- [Example](http://gaia-components.github.io/gaia-list/)

## Usage

Settings style list

```
<gaia-list>
  <a>
  <i data-icon="brightness"></i>
  <h3 flex>Menu 1</h3>
  <i data-icon="forward-light"></i>
  </a>
</gaia-list>
```

List with switch and divider

```
<gaia-list>
  <li class="ripple">
    <label flex flexbox for="wifi-switch">
      <i data-icon="wifi-4"></i>
      <h3>Wifi</h3>
    </label>
    <gaia-switch id="wifi-switch" class="divided"></gaia-switch>
  </li>
</gaia-list>
```

Contacts style list

```
<gaia-list>
  <a>
    <div>
      <h3>Noah Green</h3>
      <p>Atsara Kitchens</p>
      <div class="face"></div>
    </div>
  </a>
</gaia-list>
```

Email style list (with time stamp)

```
<gaia-list>
  <a class="unread">
    <div>
      <h3>Will Gordan</h3>
      <p>Send photos please!</p>
      <p>You're the best, thank you so much for all</p>
      <time>11:30AM</time>
    </div>
  </a>
  <a>
    <div>
      <h3>Michael Stanford</h3>
      <p>You might like this or not?</p>
      <p>Great find, I definitely check with Brian if</p>
      <time>11:30AM</time>
    </div>
  </a>
</gaia-list>
```

### ripple

Put `ripple` in class list will force trigger the ripple effect.

Put `a` href in content will trigger the ripple effect automatically.

Put `no-ripple` in class list will force NOT trigger the ripple effect.

### flexbox

Defines the element as a `display: flex`.

### flex

Expands element to fill available space `flex: 1`

## Lint check

Run lint check with command:

`$ npm run lint`
