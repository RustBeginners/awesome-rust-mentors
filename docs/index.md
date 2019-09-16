{% include ../README.md %}

<script>
let people = [];
let e = document.getElementById("mentors");
while (e.nodeName != 'H3') { e = e.nextSibling; }
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
</script>
