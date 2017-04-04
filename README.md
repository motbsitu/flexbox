# Learn Flexbox
### Flexbox course from Wes Bos
- display: flex
- flex direction - either row, column, row-reverse, or column-reverse.  Row is default
- flex wrap - using width and margin on the items
- ordering - use order and number to specify order
- Alignment/Centering
  - justify content. To add space between when on column direction, need to have height in container, size of box needs to be small enough, and justify set to space-between or space-around
  - align-items
  - align-content - have to have wrap on container and width on flex items

- Sizing
  - In flex item. flex: 1 - all take equal amount, flex: 2 - takes up 2x amount, etc.

- Grow, Shrink, basis

- Flex-basis and wrap together
  - have to apply wrap for basis to work
  - flex-grow, wrap, and basis only work on row they are on
  - when have flex direction of column, to fill all space need min-height
    - to wrap need height only (not min or max)
