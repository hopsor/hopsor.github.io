---
layout: post
title:  "I made a Scrabble like game with Phoenix LiveView"
---

<img src="{{ "/assets/posts/livewords.png" | relative_url }}" style="display: block; margin: 0 auto" />

Over the past few weeks, I’ve been diving into Phoenix LiveView, and it’s been a lot of fun! The timing couldn’t be better, as last night marked the [release](https://phoenixframework.org/blog/phoenix-liveview-1.0-released) of the final 1.0 version of LiveView. Having worked on a project with it, I feel like this is my way of celebrating LiveView's 1.0 milestone.

[LiveWords](https://livewords.fly.dev) ([Repo](https://github.com/hopsor/scrabblex)) is an open-source version of the popular board game Scrabble. It’s built with [Elixir](https://elixir-lang.org), using [Phoenix LiveView](https://github.com/phoenixframework/phoenix_live_view) and [Tailwind CSS](https://tailwindcss.com), and features only about 40 lines of JavaScript to handle tile drag-and-drop events. The rest of the codebase is purely Elixir.

The primary goal of this project was to scratch my own itch: exploring LiveView, sharing my learnings, and iterating on the project to deepen my understanding.

<img src="{{ "/assets/posts/livewords-screenshot.png" | relative_url }}" style="display: block; margin: 0 auto" />

Feel free to fork the repo, share your feedback by opening issues or pull requests, or contribute in any way you find interesting. And of course, don’t forget to play the game with your friends! If you’re flying solo, no worries—there’s always an open match waiting for you in the [listing](https://livewords.fly.dev/matches). 😄

In upcoming posts, I plan to share insights into different aspects of the project that I think will be valuable. Stay tuned!