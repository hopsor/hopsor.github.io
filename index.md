---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

## About

Hi, my name is Víctor and I'm a pasionate full stack web developer.

I started my career doing PHP but swiftly (thank god) moved on to doing [Rails](http://rubyonrails.org/)
and don't plan to look back. For the last 2 years I have been lucky enough to work in [Elixir](https://elixir-lang.org/) and its wonderful web framework [Phoenix](http://phoenixframework.org/).

On the frontend I have experience with [React](https://reactjs.org/),
[Redux](https://redux.js.org/) but my current favorite frontend framework would
have to be [Elm](http://elm-lang.org/).

As well as standard tools like the above I also enjoy using tools that might not
commently be used in development. I.e Using google docs, google apps script and
slack bots to automate things like staging environments or the management of a newsletter.


## What is important for me

 - Self organised teams.
 - Remote friendly environment.
 - Ability to think outside the box.
 - Use the right tools for the job.
 - Continuous integration AND continuous deployment.


## Worth to mention

- 2006: Created my first website [VersosPerfectos](http://versosperfectos.com/)
which became the most complete hip-hop database in Spain.
- 2013: Became partner and CTO of Diacode where I led the engineering efforts
for a dozen of projects, helping startups from Europe and US to develop and ship
their products.
- 2016: Featured on [Elixir Radar Issue 59](https://app.rdstation.com.br/mail/d9e87346-37d6-4b59-aaa9-082ff6c0d3f9).


## Writing

I write less often that I would like but from time to time I manage to put together a bunch of words about programming related stuff.

Below you can find a list of posts I've written:

{% for post in site.data.posts %}- [{{ post.title }}]({{ post.url }})
{% endfor %}
