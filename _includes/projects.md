### [Turtle](https://turtle.rs/) - Create Animated Drawings Quickly and Easily in Rust
* **Repo**: https://github.com/sunjay/turtle
* **Contact**: https://turtle.zulipchat.com/
* **Spoken Languages**: English, _Canadian English_
* **Recommended Experience**: Beginner - Intermediate
* **Topics**: 2D Computer Graphics, Game Engine, Interprocess-Communication, Async, WebAssembly

### [Dotenv-linter](https://dotenv-linter.github.io) - ⚡️ Lightning-fast linter for `.env` files. Written in Rust 🦀
* **Repo**: https://github.com/dotenv-linter/dotenv-linter
* **Contact**: https://twitter.com/mgrachev
* **Spoken Languages**: English
* **Recommended Experience**: Beginner
* **Topics**: CLI, Linters, Dotenv

<h1 id="projects-end"></h1>

<script>
var people = [];
var e = document.getElementById("project-mentorship");
while (e.nextSibling.nodeName != 'H3') e.nextSibling.remove();
e = e.nextSibling;
do {
    let person = [];
    do {
        person.push(e);
        e = e.nextSibling;
    } while (!/^H[123]$/i.test(e.nodeName));
    people.push(person);
} while (e.nodeName == 'H3');
for (let i = people.length - 1; i > 0; i--) {
    const j = Math.floor(Math.random() * (i + 1));
    [people[i], people[j]] = [people[j], people[i]];
}
people.forEach(person => {
    person.forEach(x => {
        e.parentNode.insertBefore(x, e);
    });
});
e.remove();
</script>
