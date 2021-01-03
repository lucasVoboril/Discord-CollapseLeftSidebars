[Source: reddit post](https://www.reddit.com/r/discordapp/comments/acog0e/remove_minimum_size_of_discord_window_windowsmac/)

---

We need to append lines in this file

> %appdata%/discord/settings.json

---

<table>

  <tr>
    <th> <h3> Original file </h3> </th>
    <th> <h3> Edited file </h3> </th>
  </tr>

  <tr>
    <td>
      <pre><code>{
  "IS_MAXIMIZED": false,
  "IS_MINIMIZED": false,
  "WINDOW_BOUNDS": {
    "x": 500,
    "y": 23,
    "width": 940,
    "height": 877
  }
}</code></pre>
    </td>
    <td>
      <pre><code>{
  "IS_MAXIMIZED": false,
  "IS_MINIMIZED": false,
  <b>"MIN_WIDTH": 0, </b>
  <b>"MIN_HEIGHT": 0, </b>
  "WINDOW_BOUNDS": {
    "x": 500,
    "y": 23,
    "width": 940,
    "height": 877
  }
}</code></pre>
    </td>
  </tr>

</table>
