---
title: Markdown Cheat Sheet
description: A quick reference to the Markdown syntax.
last_modified_at: 2021-12-05
---

## Overview

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can't cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](/basic-syntax) and [extended syntax](/extended-syntax).

## Basic Syntax

These are the elements outlined in John Gruber's original design document. All Markdown applications support these elements.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Element</th>
      <th>Markdown Syntax</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="">Heading</a></td>
      <td><code># H1<br>
          ## H2<br>
          ### H3</code></td>
    </tr>
    <tr>
      <td><a href="">Bold</a></td>
      <td><code>**bold text**</code></td>
    </tr>
    <tr>
      <td><a href="">Italic</a></td>
      <td><code>*italicized text*</code></td>
    </tr>
    <tr>
      <td><a href="">Blockquote</a></td>
      <td><code>> blockquote</code></td>
    </tr>
    <tr>
      <td><a href="">Ordered List</a></td>
      <td><code>
        1. First item<br>
        2. Second item<br>
        3. Third item<br>
      </code></td>
    </tr>
    <tr>
      <td><a href="">Unordered List</a></td>
      <td>
        <code>
          - First item<br>
          - Second item<br>
          - Third item<br>
        </code>
      </td>
    </tr>
    <tr>
      <td><a href="">Code</a></td>
      <td><code>`code`</code></td>
    </tr>
    <tr>
      <td><a href="">Horizontal Rule</a></td>
      <td><code>---</code></td>
    </tr>
    <tr>
      <td><a href="">Link</a></td>
      <td><code>[title](https://www.example.com)</code></td>
    </tr>
    <tr>
      <td><a href="">Image</a></td>
      <td><code>![alt text](image.jpg)</code></td>
    </tr>
  </tbody>
</table>

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Element</th>
      <th>Markdown Syntax</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="">Table</a></td>
      <td><code>
          | Syntax      | Description |<br>
          | ----------- | ----------- |<br>
          | Header      | Title       |<br>
          | Paragraph   | Text        |
      </code></td>
    </tr>
    <tr>
      <td><a href="">Fenced Code Block</a></td>
      <td><code>```<br>
      {<br>
      &nbsp;&nbsp;"firstName": "John",<br>
      &nbsp;&nbsp;"lastName": "Smith",<br>
      &nbsp;&nbsp;"age": 25<br>
      }<br>
      ```
      </code></td>
    </tr>
       <tr>
      <td><a href="">Heading ID</a></td>
      <td><code>### My Great Heading {#custom-id}</code></td>
    </tr>
    <tr>
      <td><a href="">Definition List</a></td>
      <td><code>
        term<br>
        : definition
      </code></td>
    </tr>
    <tr>
      <td><a href="">Strikethrough</a></td>
      <td><code>~~The world is flat.~~</code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#emoji">Emoji</a><br>(see also <a href="/extended-syntax/#copying-and-pasting-emoji">Copying and Pasting Emoji</a>)</td>
      <td><code>
        That is so funny! :joy:
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#highlight">Highlight</a></td>
      <td><code>
        I need to highlight these ==very important words==.
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#subscript">Subscript</a></td>
      <td><code>
        H~2~O
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#superscript">Superscript</a></td>
      <td><code>
        X^2^
      </code></td>
    </tr>
  </tbody>
</table>
