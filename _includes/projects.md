### [Crates.io](https://crates.io/) - Rust Package Registry
* **Repo**: https://github.com/rust-lang/crates.io
* **Contact**: ops > #crates-io channel on https://discord.gg/rust-lang
* **Spoken Languages**: English
* **Recommended Experience**: Beginner - Expert
* **Topics**: Web servers, databases, // TODO Sian fill this out

### [Turtle](https://turtle.rs/) - Create Animated Drawings Quickly and Easily in Rust
* **Repo**: https://github.com/sunjay/turtle
* **Contact**: https://turtle.zulipchat.com/
* **Spoken Languages**: English, _Canadian English_
* **Recommended Experience**: Beginner - Intermediate
* **Topics**: 2D Computer Graphics, Game Engine, Interprocess-Communication, Async, WebAssembly

<h1 id="projects-end"></h1>

<script>
let people = [];
let e = document.getElementById("project-mentorship");
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
