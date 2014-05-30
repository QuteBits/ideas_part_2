Qute Hack Ideas (Part 2)
===

_Hint 1:_ Contributions and corrections (I'm not a native english speaker) are welcome!  
_Hint 2:_ Proposals to work on one of the ideas are welcome too.

Somewhere in 2011 I've started to write down ideas that appeal to my taste. Here is a small batch (7 ideas):

## 8. Wireshark Pong GUI

Look at [this visualization](https://www.youtube.com/watch?v=hNjdBSoIa8k) of a DOS attack using [Logstalgia](https://code.google.com/p/logstalgia/). Now look at [Wireshark GUI](http://youtu.be/NHLTa29iovU?t=5m45s). While Wireshark is an awesome tool - how awesome would it be to catch the latest captured packets from it (using tail, for example) and show it in a browser tab (using WebGL, for example)? Using the monster feature of filtering packets in Wireshark, we could simply SEE things happening, not READ them.

It seems to be an interesting question, whether there are other types of traffic (like DOS attacks) that could be quickly identified visually by just taking a glimpse on such a visualization.

## 9. Wireshark Pong GUI Snippets

In the spirit of [WebGL Playground](http://webglplayground.net/gallery), create a place where you could publish visualizations from Idea 8.

## 10. Broken Links Checker

Have a blog? Or even better - have a blog you've coded yourself? Then you know what I'm talking about. That YouTube video you posted a year ago, is banned. The link to that cool essay on some other blog - broken. The link to some cute photo? Broken. Someone has to solve this problem. In a platform-agnostic way.

## 11. Reverse CSS

When you have tons of CSS on your page, the amount of different selectors exceeds the amount of possible CSS properties. So it seems to be adequate to NOT ONLY be able to look into some '.nifty-class' selector and look if there is some 'padding-left' assigned - but to lookup the 'padding-left' property and see if '.nifty-class' is included.

*Example:*

```css
/*Instead of:*/
.nifty-class {
  padding-left: 5px;
  float: left;
}
#lame-id {
  padding: 8px;
}

/*you should also be able to alter:*/
padding-left {
  .nifty-class: 5px;
  #lame-id: 8px;
}
```

## 12. Games Screening Cafe

When people wait for their favorite coffee to be made or eat their favorite breakfast bagel - why not place a huge screen somewhere on the wall, screening latest League of Legends championship or best Starcraft 2 duels or someone like [TheRadBrad](https://www.youtube.com/user/theRadBrad) playing some [really oldschool stuff](https://www.youtube.com/watch?v=ueUjl-j59T8)? I mean, geeks will feel themselves at home there. And there are lots of us, trust me.

## 13. Grid Madness

Imagine some very simple [Top-Down 2D Multiplayer shooter](https://www.youtube.com/watch?v=ho1hviRRT8A) where you could assemble your own guns from... MATH FUNCTIONS. Imagine assembling a Railgun simply with "y=0" or being killed by a Sinus-Gun. Or dropping some function-alternating grenade ("+2x Grenade, for example), changine enemies "y=sin(x)" gun to a "y=sin(x) + 2x" gun for a couple of seconds. Not sure how far that could go but creating a gun that takes derivatives of enemies functions or a rocket launcher hitting "x^2 + y^2 = z from {0;1;2;3}" sounds awesome.

*Examples of usage:*

 * Show it to people at school and ask if functions arent fun?

## 14. Recognize Similar Fonts

Ever wanted to copy that awesome font the ad you've seen last night? Why not create a [Shazam](https://www.shazam.com) for fonts?
