---
permalink: /docs/hunts/relaying
title: "Relaying"
last_modified_at: 2022-01-02T08:48:05-04:00
toc: true
sidebar:
  nav: "docs"
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/althaion_waeth_rainbow_dance.png
  caption: "Photo credit: **Al'thaion Waeth**"
  image_description: "Pictured: Al'thaion Waeth and Kivarstra Suhgrest"
---
⚠️ 12/28/21: This guide is still Work in Progress but should still provide some use for you.
{: .notice}

# Overview
The information below should help you get started on how to relay out calls for hunts, fates and other special oveworld events in the game. We have example macros, suggestions on different things you can relay and I will be posting all of my macros below as well. If anything looks weird, try copy and pasting it in to the game and it should look correct afterwards.

# Recommended Macros

## Fates

{% include codeHeader.html %}
```
Look! An achievement fate ☆☆<flag>☆☆
```
{% include codeHeader.html %}
```
Look! An achievement fate ☆☆<flag>☆☆ It Drops: Glamour as well!
```
{% include codeHeader.html %}
```
Look! An achievement fate ☆☆<flag>☆☆ It Drops: a Minion as well!
```
{% include codeHeader.html %}
```
Look! An achievement fate ☆☆<flag>☆☆ It Drops: A Triple Triad card as well!
```
{% include codeHeader.html %}
```
Look! An achievement fate ☆☆<flag>☆☆ It Drops: Barding as well!
```
{% include codeHeader.html %}
```
Ishgard FATE!! 5 min!
```
{% include codeHeader.html %}
```
SPECIAL FATE <flag>
```
{% include codeHeader.html %}
```
Fate is dead!
```

## Hunts
{% include codeHeader.html %}
```
Ooh Look! A hunt train! <flag>
```
{% include codeHeader.html %}
```
S Rank Hunt Target <flag> 
```
{% include codeHeader.html %}
```
A Rank Hunt Target <flag>
```
{% include codeHeader.html %}
```
Ishgard FATE!! 5 min!
```
{% include codeHeader.html %}
```
☆★S RANK Relay★☆   →  <flag>
```
{% include codeHeader.html %}
```
★★ Rank  <flag>
```

### Adamantoise-specific macros. Helpful for cross-world linkshells!
{% include codeHeader.html %}
```
- at <flag> on 
```
{% include codeHeader.html %}
```
Special  FATE  <flag> on 
```
{% include codeHeader.html %}
```
An  hunt train is starting at <flag>. An  hunt train!
```

### Hunt train macros
(These are all examples from current conductors, so feel free to take creative liberties as you desire!)

We recommend a 15 minute heads up before the train
{% include codeHeader.html %}
```
(*-ω-)zzz <<15 Minute warning~ Dump your seals/powetics and meet us at <flag> >> 
```

And then a macro when the time starts to announce it's starting. (The `/wait` lines are important, since the game will stop your macro if it thinks you're spamming in specific chat channels.)
{% include codeHeader.html %}
```
Ooh Look! A hunt train! <flag>
```

Then a macro to begin your train, usually with rules and guidance:
{% include codeHeader.html %}
```
 /shout Thank you for coming to our Adamantoise train sponsored by The Adamantoise Hunters Association!
 /wait 2
 /shout While on Ada, we ask that you do not link ahead of the conductors and you do not use shout for LFG.
 /wait 2
 /shout Please use PF for a group. If there are no groups, please make one. 
Feel free to shout out the names of groups in PF. Thank you for your understanding! 
 /wait 2
 /shout Train will be starting     :tm:
```

You will want a macro to denote the next stop
{% include codeHeader.html %}
```
Next stop <flag>
```

Some also use macros to announce when the target has been attacked (make sure you use it while targeted on the mark)
{% include codeHeader.html %}
```
STRIKE IT, BURN IT!! <t> engaged <thpp> health! <flag>
```

Vibe checks, if you run them (I'd suggest them for busier trains/SB trains to allow for full loading and to let everyone get a shot at the mob)
{% include codeHeader.html %}
```
 Load in check <flag>
 ```

A "Last stop" macro comes in handy as well
{% include codeHeader.html %}
```
Last Stop!! Thanks all for coming <3 <flag>
```
{% include codeHeader.html %}
```
Final target!♡ -> <flag>
```

And maybe one to relay when you make an oopsie. We're all human...
{% include codeHeader.html %}
```
 ATTENTION  Please ignore that last link. Either the location was wrong, the fate/spawn is dead, or I'm just dumb and/or clumsy.
```


# MISC

## Block letters
When you copy/paste them in to the game macro box, the boxes below spell out useful stuff! It'll look like a bunch of spammy blocks, but copy/paste them in to an extra macro slot for quick reference.

[Althaia's Macro/Block Letter generator](https://althaiadev.github.io/ffxiv-block-chars/) - helps make block letter macros and will be expanded to generate hunt macros in the future!

Other block letter resource: [Othelia's IMGUR](https://imgur.com/gallery/fxXlDTr)