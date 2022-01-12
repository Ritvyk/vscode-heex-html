# Heex-HTML

HEEX HTML extension for phoenix framework 🚀, it supports syntax for **Alpine JS** and **Phoenix** Control Keywords out of the box with new **HEEX** syntax.

## Features

Theme used for examples - ```Monokai Dimmed```.

>### HEEX Support ⭐
supports new HEEX engine syntax highlighting out of the box.
![Alpine Support](/src/heex_component.gif)
>### Alpine JS embedded support out of the box 😻

 supports alpine ``` @actions ``` and syntax for ```x-* ```

 #### Bugs
1. Sometimes breaks when using elixir string interpolation between alpine code string.
2. No syntax highlighting for more than 2-3 nested ```""```

![Alpine Support](/src/alpine_support.gif)


>### Phoenix Attributes embedded support out of the box 😻

 supports syntax ```phx-* ``` inside HTML tags with all new ```HEEX {}``` interpolation and regular ``` LEEX ``` ``` <%= %> etc ``` inside HTML.

 #### Bugs
1. does not support if ``` <%=``` etc used inside HTML tags as of new HEEX engine in phoenix .


![Elixir Support](/src/elixir_support.gif)

## Note
 Open to **PRs** to repo as this is an initial version and can become more powerfull in the future.

**Enjoy!**
