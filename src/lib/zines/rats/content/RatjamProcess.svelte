<template>
  <br>

  <div class="positioner">
    <h1>how the rat gets made</h1>

    <p>
      on October 16, while waiting for a C train that took more than an hour to come, I (fran) recorded a few videos of rats in
      the station. I will include a couple of them here (compressed so that the website doesn't get too heavy)
    </p>

    <img src="/zines/rats/ratvid1.gif" alt="a rat in the subway scurrying out of sight" />
    <img src="/zines/rats/ratvid2.gif" alt="a momma rat with her baby" />
    <img src="/zines/rats/ratvid3.gif" alt="a rat scurrying towards a shaky camera person" />

    <p>there seemed to be two rats, a larger one and a smaller one. i like to believe it was a momma rat and her baby</p>
    <p>
      i was lucky enough to have the momma rat skitter past me in that last video. this last video is what was eventually used as
      the source material for the animated rat in the piece
    </p>

    <p>
      originally, i'd recorded these because i was working on a one-week <a href="https://frojo.itch.io/ratcraft">RTS prototype</a
      > and wanted some rat assets for it
    </p>
    <p>mut saw this prototype and i mentioned that i tried to animate the rats, but it was too much work to figure it out</p>
    <p>later that night, mut DM'd me asking for the video</p>
    <p>and then he cropped out a little loop of animation</p>
    <video muted autoplay>
      <source src="/zines/rats/ratanim.mp4" type="video/mp4" />
    </video>
    <img src="/zines/rats/ratanim.gif" alt="a rat scurrying towards a shaky camera person" />
    <p>i started updating the game with the gif, but that ended up getting deprioritized for other work</p>
    <p>about a month later, pondlife decided to make this zine, and we decided the theme would be rats</p>
    <p>
      we're sitting in the room that we do work in together. i think mut has the idea that we should all work on a game together
      "at the same time".
    </p>
    <p>
      mut sets up a 10-minute timer on his computer. the rule is we each had 10 minutes to do whatever we wanted, but when the
      timer runs out, we hand over to control to someone else. the rest of us sit around and watch and are free to comment or work
      on something else
    </p>
    <p>
      i forget exactly how we arrived on the idea of rotoscoping the rat gif. we brought the rat gif into blender and traced it
      frame by frame. I'm pretty sure we all did some tracing. we continued like this for about an hour until we traced all the
      frames
    </p>
    <p>different people had different tracing styles. at some point ali gave the rat a mickey mouse tatto on their butt</p>
    <p>
      ali was working on a website experiment, and the rest of us would take turns helping her while we weren't tracing the rat
    </p>
    <p>
      when we were done tracing, we switched back to coding. we wrote some quick javascript that would loop over all the frames
      and animate the rat. and some code to make the rat follow the cursor, and eventually made the cursor a cheese emoji
    </p>
    <p>
      i left at around this point while the rest of pondlife kept working.
      </p>
      <p>
      mut told me that at about the same time that i left, it was ali's turn on the computer. she opened some digital painting software and painted something. but then she didn't like it so she started covering it up with another painting. but when her time was up, mut painted over that, trying to recreate the original painting that ali didn't like.
    </p>
    <p>
    then he added this painting as the background
    </p>
  </div>
</template>

<style>
  /* copy some zine styles */
  .positioner {
    width: 80%;
    margin-top: 41px;
    padding-left: 20px;
    padding-right: 20px;
  }

  /* get back the normal spacings */
  h1 {
    margin-top: 20px;
    margin-bottom: 20px;
  }

  h1,
  p {
    margin-top: 16px;
    margin-bottom: 16px;
  }

  img,
  video {
    width: 100%;
  }
</style>
