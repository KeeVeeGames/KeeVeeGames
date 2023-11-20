### Hi there 👋

[![Donate](https://img.shields.io/badge/donate-%E2%9D%A4-blue.svg)](https://musnik.itch.io/donate-me) [![Twitter Follow](https://img.shields.io/twitter/follow/KeeVeeGames?label=Follow&logo=twitter)](https://twitter.com/intent/user?screen_name=KeeVeeGames)

I am Nikita Musatov (also know as MusNik and KeeVee Games) a full-time professional GameMaker developer located in Armenia. I do videogames, assets for GML programmers, open-source libraries/examples, and contract freelance work! Worked on [Voidigo](https://store.steampowered.com/app/1304680/Voidigo/), [RetroMania Wrestling](https://www.retromaniawrestling.com/), [ScreenPlay](https://store.steampowered.com/app/1830700/ScreenPlay/), [Norland](https://store.steampowered.com/app/1857090/Norland/) and [other](https://www.linkedin.com/in/musnik/details/experience/) projects.

<img align="right" alt="GIF" src="http://keevee.games/wp-content/uploads/2019/06/keeveelogo.gif" width="33%"/>

- 👨‍💻 Currently working on GooWee.gml [<sup>?</sup>](#! "Advanced and clean GUI framework inspired by WPF and Unity GUI") and GmProto [<sup>?</sup>](#! "Protobuf / flatbuffers-esque serialization protocol")
- 🕹 Producer and Lead Programmer of [Close Your Eyes](https://twitter.com/KeeVeeGames)
- 📦 Assets I made: on [Marketplace](https://marketplace.yoyogames.com/publishers/1227/keevee-games) and [Itch.io](https://musnik.itch.io/)
- 💾 Other languages I know and work with: C++, C#, Javascript, GLSL, Java, etc.
- 📖 Visit my [Portfolio](https://forum.yoyogames.com/index.php?threads/keevee-games-gml-programming-and-game-development-services.22402/) and [Showcase](https://twitter.com/KeeVeeGames/timelines/1620165755814780931)
- 📫 Contact to hire me or ask questions: support@keevee.games

<sub>Contributions: [GameMaker-HTML5](https://github.com/YoYoGames/GameMaker-HTML5), [GMEdit](https://github.com/YellowAfterlife/GMEdit), [painfully-learned-lessons](https://github.com/JujuAdams/painfully-learned-lessons), [tex-pack](https://github.com/GameMakerDiscord/tex-pack), [buffer-zlib](https://github.com/YAL-GameMaker/buffer_zlib).</sub>

### Notable repos:

<table>
<thead>
<tr>
<th width="177px">Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>
<a href="https://github.com/KeeVeeGames/OKColor.gml" style="line-height: 1;"><img src="https://keevee.games/wp-content/uploads/2023/11/logo-150x150.png" alt="OKColor.gml"></a>
</td>
<td>

**OKColor** is a color management library for GameMaker written in pure GML that implements the new "industry standard" [OKLab](https://bottosson.github.io/posts/oklab/)/[OKLCH](https://evilmartians.com/chronicles/oklch-in-css-why-quit-rgb-hsl) perceptual color models, that gives better results than standard RGB/HSV. It's simple to use with only one [`OKColor`](https://github.com/KeeVeeGames/OKColor.gml/wiki/API-Reference) class and a bunch of methods providing [setting the color](https://github.com/KeeVeeGames/OKColor.gml/wiki/API-Reference#setters), [models conversion](https://github.com/KeeVeeGames/OKColor.gml/wiki/API-Reference#getters), [mixing](https://github.com/KeeVeeGames/OKColor.gml/wiki/API-Reference#mixing) and [getting the color for rendering](https://github.com/KeeVeeGames/OKColor.gml/wiki/API-Reference#color-getters).

![example](https://github.com/KeeVeeGames/KeeVeeGames/assets/10993317/c0f96311-b679-414e-8b8f-c97e1cdde88e)

</td>
</tr>
<tr></tr><tr>
<td>
<a href="https://github.com/KeeVeeGames/ArrayList.gml" style="line-height: 1;"><img src="https://keevee.games/wp-content/uploads/2020/10/logo-150x150.png" alt="ArrayList.gml"></a>
</td>
<td>

The most complete list class for GameMaker Studio 2.3+. GC-friendly, `[]` accessor, 50+ functions (add, remove, insert, contains, find, sort, shuffle, reverse, copy, clone, etc.) and reference as array.

```js
list = new ArrayList();

list.add("howdy", "ho", "world", "!").remove_at(1); // method chaining is also supported
list.array[0] = "hello";
```

</td>
</tr>
<tr></tr><tr>
<td>
<a href="https://github.com/KeeVeeGames/DuplicateSequence.gml"><img src="https://keevee.games/wp-content/uploads/2023/06/logo-150x150.png" alt="DuplicateSequence.gml"></a>
</td>
<td>

Create a deep copy of Sequence and modify its properties in-game without changing the original resource! Useful for using sequences as templates for graphics elements and UI with changeable placholders.

```js
var seq_new = sequence_duplicate(seq_orig);
seq_new.tracks[0].keyframes[0].channels[0].text = "Hello World";
// this will not change the original sequence property!
```

</td>
</tr>
<tr></tr><tr>
<td>
<a href="https://github.com/KeeVeeGames/DeepCopy.gml"><img src="https://keevee.games/wp-content/uploads/2020/12/logo-150x150.png" alt="DeepCopy.gml"></a>
</td>
<td>

Deep clone class instances, anonymous structs and arrays nested in any order!

```js
var thing = new Class();
thing.something = { first : [0, 1, 2], second : [3, 4, 5] };

// will return a new Class instance with the identical values but new references
var new_thing = deep_copy(thing);
```
</td>
</tr>
<tr></tr><tr>
<td>
<a href="https://github.com/KeeVeeGames/Exception.gml"><img src="https://keevee.games/wp-content/uploads/2023/05/logo-150x150.png" alt="DeepCopy.gml"></a>
</td>
<td>

Base class for custom exceptions replicating a structure of system exceptions and adding better support of [try-catch](https://manual-en.yoyogames.com/GameMaker_Language/GML_Overview/Language_Features/try_catch_finally.htm) and [exception_unhandled_handler](https://manual-en.yoyogames.com/GameMaker_Language/GML_Reference/Debugging/exception_unhandled_handler.htm) for these custom exceptions.

The class is generating all the necessary exception fields and populates data for `script`, `line` and `stacktrace` ones. Makes output on error windows nicer and more meaningful on handled exceptions. Also adds better support for YYC.

</td>
</tr>
<tr></tr><tr>
<td>
<a href="https://github.com/KeeVeeGames/foreach.gml"><img src="https://keevee.games/wp-content/uploads/2020/10/logo-1-150x150.png" alt="foreach.gml"></a>
</td>
<td>

foreach() loop implementation on GameMaker Studio 2.3+ for arrays, ds_lists, ds_maps, ds_stacks, ds_queues, ds_priorities and structs. Syntax is pretty neat and straightforward:

```js
foreach(collection as (item) {
    // do things with item
});
```

</td>
</tr>
</tbody>
</table>
