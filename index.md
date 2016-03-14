---
layout: default
---

<h1><a href="{{ site.baseurl }}/">{{ site.title }}</a></h1>

[Ruse][ruse-lang] is an embedded Scheme for Rust, like Lua is for C. It is currently in development, and can be [found on GitHub][ruse].

Ruse is a [stress-free project][stress-free], and exists for fun, experimentation, and education. If you're interested in seeing how Scheme can be implemented, and in learning with other contributors about how to make a real programming language, this is the project for you.

If you're looking for a real-world-ready programming language to solve some immediate problem, best look elsewhere.

The Ruse team maintains a list of other programming languages implemented in Rust, which you [may be interested in perusing][langs-in-rust].

The code for this website is [also on GitHub][website], if you want to suggest changes.

<section>
  <h2>Development Log <a href="/feed.xml">Subscribe via RSS</a></h2>

  <ol class="posts">
    {% for post in site.posts %}
      <li class="post">
        <h3>
				  <a href="{{ post.url }}">{{ post.title }}</a>
				  <span class="meta">
					  Posted on {{ post.date | date_to_string }}
				  </span>
			  </h3>
      </li>
    {% endfor %}
  </ol>
</section>

[ruse-lang]: https://github.com/ruse-lang/
[ruse]: https://github.com/ruse-lang/ruse
[stress-free]: https://github.com/ruse-lang/stress-free-manifesto
[langs-in-rust]: https://github.com/ruse-lang/langs-in-rust
[website]: https://github.com/ruse-lang/ruse-lang.github.io

