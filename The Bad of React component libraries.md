# "The Bad" of React component libraries

First off, this is just a list of negatives. These libraries will also have advantages compared to each other which aren't listed here, and could make them actually be reasonable choices.

Specifically, latest **Material UI** is a "good" library, if it's not a problem for you that it's a little heavy.

In the current list, MUI is the only one I'd generally recommend.

## Blueprintjs

- Doc examples don't include required and relevant imports.
- Doesn't obviously support separate imports for components.
- Functionality dependent on project using a specific style solution.
  - Navbar `position: fixed` option only gives required body padding size as a sass variable.

## React Toolbox

- Doesn't really care about accessibility.
- Slow maintenance (bug fixes, obviously needed features).
  - Partially due to being driven primarily by a single maintainer/author.

## Material UI

- Not a huge accessibility focus.
- Slightly heavy css-in-js solution. (JSS)

## Material UI v0.x

- Not a huge accessibility focus.
- Uses inline styles for everything.
  - Can't override with css, has bad performance for non-trivial pages. Can't use animations.

## React Bootstrap

- Getting started link broken?
- Uses default Bootstrap css (or scss, options!), so styles are not in any way scoped and will bleed into other html.
- Doc examples don't show imports, but they are shown in the docs API (props) section.
