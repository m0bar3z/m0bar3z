I want to centre them, however, wrapping them in a <div align='center'></div> only displays the raw links and not the shield images.

In GitHub's GFM, you'll need to separate your opening and closing <div> tags from your Markdown with blank lines:

<div align="center">

  <a href="">![example1](https://img.shields.io/badge/example-one-red)</a>
  <a href="">![example2](https://img.shields.io/badge/example-two-green)</a>
  <a href="">![example3](https://img.shields.io/badge/example-three-blue)</a>

</div>
