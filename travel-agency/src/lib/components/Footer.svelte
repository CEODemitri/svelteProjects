<div class="container">
    <section>
        <h4>Trek</h4>
        <p>Book your next trip in minutes. The power is in your hands.</p>
        <div class="socials">
            <div></div>
            <div></div>
            <div></div>
            <div></div>
        </div>
    </section>

    <section>
        <article>
            <h5>Company</h5>
            <ul>
                <li>About</li>
                <li>Careers</li>
                <li>Blog</li>
                <li>Special Offers</li>
            </ul>
        </article>

        <article>
            <h5>Help</h5>
            <ul>
                <li>FAQ</li>
                <li>Help Center</li>
                <li>Privacy Policy</li>
            </ul>
        </article>

        <article>
            <h5>Partner</h5>
            <ul>
                <li>Partner Hub</li>
                <li>Affiliates</li>
                <li>Advertise</li>
            </ul>
        </article>
        
    </section>
</div>

<style>
    * {
        padding: 0;
        background-color: rgb(33, 28, 63);
        color: white;
        font-family: Arial, Helvetica, sans-serif;
    }

    .container {
        width: 100%;
        display: flex;
        padding: 20px;
        justify-content: space-around;
    }

    @media (max-width: 760px) {
        .container {
            gap: 100px;
        }

        section:last-of-type {
            gap: 20px;
        }
    }

    p {
        font-size: 0.8rem;
        width: 180px;
    }

    .socials {
        display: flex;
        gap: 10px;
    }

    .socials > div {
        height: 30px;
        width: 30px;
        background-color: antiquewhite;
        border-radius: 50%;
    }

    section:last-of-type {
        display: flex;
        gap: 20px;
        padding: 0 20px 0 0;
    }

    ul {
        list-style: none;
        display: flex;
        flex-direction: column;
        gap: 5px;
        font-size: 0.8rem;
    }
</style>
