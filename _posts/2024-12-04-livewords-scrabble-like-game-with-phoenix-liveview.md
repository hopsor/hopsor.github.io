---
layout: post
title:  "I made a Scrabble like game with Phoenix LiveView"
---

<img src="{{ "/assets/posts/livewords.png" | relative_url }}" style="display: block; margin: 0 auto" />

In the last weeks I've been having some fun with Phoenix LiveView. The outcome of this couldn't come in a better moment as last night the final 1.0 version of LiveView was [released](https://phoenixframework.org/blog/phoenix-liveview-1.0-released). I enjoyed a lot working on it so to me this is a celebration of LiveView's 1.0 milestone.

[LiveWords](https://livewords.fly.dev) ([Repo](https://github.com/hopsor/scrabblex)) is an open source version of the popular board game Scrabble. It's written in [Elixir](https://elixir-lang.org) using [Phoenix LiveView](https://github.com/phoenixframework/phoenix_live_view) and [Tailwind CSS](https://tailwindcss.com). It has barely 40 lines of javascript to handle the drag and drop events of the tiles. Everything else is Elixir code.

My intention with this was essentially scratching my own itch, playing with Live View, sharing my learnings and keep iterating to improve it as much as I can to continue my learning process.

<img src="{{ "/assets/posts/livewords-screenshot.png" | relative_url }}" style="display: block; margin: 0 auto" />

Feel free to fork it, share feedback by opening issues, PRs or anything that you consider interesting. Of course, don't forget to play with your friends. And, if you don't have any, you can always find open matches in the [listing](https://livewords.fly.dev/matches) 😀

In the next posts I plan to write about different aspects of the project that I consider relevant to share.