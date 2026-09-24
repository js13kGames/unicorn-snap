---
genres:
  - simulation
  - casual
directors_cut: https://www.gamedev.pl/play/unicorn-snap
video: https://youtu.be/dfZDOYhNlPU
# See github.com/js13kGames/hello-world for supported frontmatter
---

My daughter played [Rainbow Surfer](https://js13kgames.com/2026/games/rainbow-surfer), my other entry this year, and told me the unicorn was nice but you never get to look at it, because you are going too fast. She wanted a game where you take photos of it instead. So we made one, and she tested every version.

You are a photographer with one client. First you dress her up: paint the mane, tail, coat, horn and hooves, and add glitter. Then you get eight photos while she moves around the studio.

What you paint changes what she does. Warm colours make her show off, so you get prancing, rearing and mane tossing. Cool colours make her calmer, and she bows and looks at the camera more. Glitter makes her shake it out, and glitter in the air makes the best photos.

The flash wakes her up. Right after a shot she is more likely to do something worth photographing, so a photo you waste can buy you a better one. If you stop shooting she gets bored and lies down.

The score never looks at the pixels. Each photo is judged on what was happening when you pressed the button: where she was in the frame, how big she was, what she was doing, and whether she was looking at you. The same photo twice is worth less than two different ones, so walk around her.

At the end you see all your photos, each with a thumbs up or down and one line saying why. Three sessions make a season, and the season total is your score.

Controls: drag to aim, pinch or scroll to zoom, tap (or space, or the big round button) to take the photo. On a keyboard, Q and E walk around her and W and S zoom. The small button next to the shutter flips the left and right drag if you prefer it the other way round.

Technical: plain WebGL, one shader, no libraries, no image or sound files. The unicorn is a set of boxes. The mane and tail are chains of points with simple physics, pushed out of her body by the same boxes you can see. The shadow uses the stencil buffer. The studio wall is one curve spun around, with the lighting baked into the colours. 13,066 bytes zipped.