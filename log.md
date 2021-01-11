# CSS training

Created a skeleton. Looking into [css position](https://www.youtube.com/watch?v=jx5jmI0UlXU) video.

**Position property:**

- static     -> default position according to HTML document flow
- relative -> same as static, but you can change its position RELATIVE to its static/document position

- absolute -> absolute position 
- fixed        -> relative to whole HTML / screen



Typical use case: parent is relative (default), children are absolute (within the parent)





**Display property:**

- inline (minimum width possible, can't set w or h)
- block (full width possible, can set h or w, takes a full row)
- inline-block (within row, but can set w or h)



**Flexbox:**

- nice [reference sheet](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

- how to prevent flexbox items (children) to prevent growing of the parent?
  - add min-height: 0



---

How to position two divs side by side?

- use two inline-blocks. But there's the [whitespace caveat](https://stackoverflow.com/questions/18262300/two-inline-block-elements-each-50-wide-do-not-fit-side-by-side-in-a-single-ro), so use **flexbox** or **css grid**.



What are CSS Grid and Flexbox and when to use which?

- grid - defines a grid/containers. Relatively new feature.



How to make top-level container full-size, non-scrollable?

- either hardcode the `top` value of bottom container + `absolute` positioning. Downside = duplicated value (header height + offset in content div)
  - breaks flexbox stuff I think
- flexbox



How to control resizing of items on the main axis?

- Mozilla documentation [here](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Controlling_Ratios_of_Flex_Items_Along_the_Main_Ax)



TODO figure out how do flexbox and image (content) size interact



Ways to make full-viewport layouts? Nice [post here](https://blog.stevensanderson.com/2011/10/05/full-height-app-layouts-a-css-trick-to-make-it-easier/)



Za tatija: https://css-for-js.dev/ 



Why do units matter so much?