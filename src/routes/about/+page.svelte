<script>
    import AboutCard from "../../components/AboutCard.svelte";

    const aboutData = [
        {
            id: 1,
            name: "Ajita Kandapu",
            email: "ajitak@usf.edu",
            contributions:
                "I entered all of the facts, prices, and descriptions for the category items into the database and developed cart page, and login/signup page.",
            image: "ajita.jpg",
        },
        {
            id: 2,
            name: "Shivani Reddy Donthireddy",
            email: "shivanireddy@usf.edu",
            contributions:
                "I have contributed to develop the database connection, cart page, and login/signup page.",
            image: "shivani.jpg",
        },
        {
            id: 3,
            name: "Nandini Bethamcharla",
            email: "nandinibethamcharla@usf.edu",
            contributions:
                "Retrieving items by category and user authentication (sign up and login) using an SQLite database and I have worked on retrieving items by category and user authentication (sign up and login) using an SQLite database.",
            image: "nandini.jpg",
        },
        {
            id: 4,
            name: "Pavan",
            email: "boppana12@usf.edu",
            contributions:
                "Inculcating the cart functionalities and checkout process followed by flawless payment process and Linking up with dataset.",
            image: "pavan.jpg",
        },
    ];
</script>

<div class="student-section">
    {#each aboutData as member (member.id)}
        <AboutCard {member} />
    {/each}
</div>

<style>
    .student-section {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        margin-bottom: 100px;
    }
</style>
