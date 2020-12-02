### Hi there 👋

[![Donate](https://img.shields.io/badge/donate-%E2%9D%A4-blue.svg)](https://musnik.itch.io/donate-me) [![Twitter Follow](https://img.shields.io/twitter/follow/KeeVeeGames?label=Follow&style=social)](https://twitter.com/intent/user?screen_name=KeeVeeGames)

I am Nikita Musatov (also know as MusNik and KeeVee Games) a full-time GameMaker developer located in Russia. I do videogames, assets for GML programmers, open-source libraries/examples, and contract freelance work!

<img align="right" alt="GIF" src="http://keevee.games/wp-content/uploads/2019/06/keeveelogo.gif" width="33%"/>

- 👨‍💻 Currently working on GooWee.gml [<sup>?</sup>](#! "Advanced and clean GUI framework inspired by WPF and Unity GUI") and GmProto [<sup>?</sup>](#! "Protobuf / flatbuffers-esque serialization protocol")
- 🕹 Lead Programmer of [@CraftisLegacy](https://twitter.com/CraftisLegacy)
- 📦 Assets I made: on [Marketplace](https://marketplace.yoyogames.com/publishers/1227/keevee-games) and [Itch.io](https://musnik.itch.io/)
- 💾 Other languages I know and work with: C++, C#, Java, Javascript, etc.
- 📖 Visit my [Portfolio](https://forum.yoyogames.com/index.php?threads/keevee-games-gml-programming-and-game-development-services.22402/) and [Showcase](https://twitter.com/i/events/1137457904213286913)
- 📫 Reach me for contract job or questions: support@keevee.games

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
<a href="https://github.com/KeeVeeGames/ArrayList.gml" style="line-height: 1;"><img src="https://keevee.games/wp-content/uploads/2020/10/logo-150x150.png" alt="ArrayList.gml""></a>
</td>
<td>

The most complete list class for GameMaker Studio 2.3+. GC-friendly, `[]` accessor, 50+ functions (add, remove, insert, contains, find, sort, shuffle, reverse, etc.) and reference as array. Example:

```js
list = new ArrayList();

list.add("howdy", "ho", "world", "!").remove_at(1); // method chaining is also supported
list.array[0] = "hello";
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
