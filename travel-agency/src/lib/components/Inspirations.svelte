<div class="container">
    <!-- top 20% -->
    <section class="header">
        <h2>Get <span>Inspirations</span> from Our Blog</h2>
        <p>Gain inspiration and insights by exploring our enriching blog content</p>
    </section>

    <!-- bottom 80% -->
    <section class="blog-container">
        <!-- TODO: Replace image placeholder -->
        <article class="main">
            <img src="../elf/blog/passports.jpeg" alt="" class="passports">
            <div class="details">
                <span>5 min Read</span>
                <h3 class="text">A Guide to Seamless Travel Planning and Booking</h3>
                <p><span class="sm-square"></span> November 2083</p>
            </div>
        </article>
        <aside>
            <article>
                <img src="../elf/blog/align.jpeg" alt="">
                <div class="details">
                    <span>5 min Read</span>
                    <h3>Travel Planning and Booking</h3>
                    <p><span class="sm-square"></span> November 2083</p>
                </div>
            </article>
            <article>
                <img src="../elf/blog/geraldTrip.jpeg" alt="">
                <div class="details">
                    <span>7 min Read</span>
                    <h3>Booking and Seamless Travel</h3>
                    <p><span class="sm-square"></span> November 2083</p>
                </div>
            </article>
            <article>
                <img src="../elf/blog/shadow.jpeg" alt="">
                <div class="details">
                    <span>11 min Read</span>
                    <h3>A Guide to Planning and Booking</h3>
                    <p><span class="sm-square"></span> November 2083</p>
                </div>
            </article>
        </aside>
    </section>

    <button class="see-more">See More</button>
</div>

<style>
    * {
        padding: 0;
        margin: 0;
        box-sizing: border-box;
    }

    .container {
        width: 95%;
        display: flex;
        flex-direction: column;
        gap: 40px;
        margin: auto;
        font-family: Arial, Helvetica, sans-serif;
    }

    span {
        color: steelblue;
    }

    section:first-of-type {
        height: 20%;
        width: 100%;
    }

    section:last-of-type {
        height: 80%;
    }

    .blog-container {
        display: flex;
        width: 100%;
    }

    .passports {
        height: 250px;
        width: 325px;
    }

    .text {
        width: 35ch;
        font-size: 1.1rem;
    }

    aside {
        display: flex;
        flex-direction: column;
        gap: 20px;
        width: 100%;
    }

    aside > article {
        display: flex;
        gap: 10px;
        border: 1px solid lightgrey;
        padding: 10px;
    }

    article > img {
        height: 100px;
    }

    .see-more {
        height: 1.8rem;
        width: 8rem;
        background-color: steelblue;
        border: none;
        border-radius: 10px 0 0 0;
        color: white;
        font-size: 0.9rem;
        margin: auto;
    }

    .details {
        display: flex;
        flex-direction: column;
        gap: 10px;
    }
</style>