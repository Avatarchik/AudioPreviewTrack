AudioPreviewTrack
=================

![screen](https://i.imgur.com/Lrc6068.png)

**AudioPreviewTrack** is a custom track for Unity Timeline that provides
instant audio playback in preview mode.

How to use
----------

1. Add an Audio Preview Track to a timeline.
2. Add an Audio Preview Clip to the preview track.
3. Set an audio clip to the Clip property of the preview clip.

Known issues and limitations
----------------------------

- Audio Preview Track only works in Editor. It doesn't anything in built apps.
- Audio Preview Track only supports a single track. It doesn't work correctly
  if there are more than two playing tracks.
- Audio Preview Clip allocates small amount of GC memory per every frame :(

Nice! But how about having a waveform visualization?
----------------------------------------------------

Waveform visualization with the standard Audio Track has been implemented in
Unity 2017.2. [Try beta] if you're interested.

[Try beta]: https://unity3d.com/unity/beta

Disclaimer!
-----------

I made this small utility just for making it easy to synchronize animation and
music when creating a music video with Unity Timeline. Please don't expect that
it's going to be more than just a utility. I used dirty and hackish tricks to
implement it, so that it's not recommended for practical purposes.

If you seriously think that this functionality is a must-have, please give a
vote to [Feedback].

[Feedback]: https://feedback.unity3d.com/

License?
--------

[Public domain](http://unlicense.org)
