<div class="value-container">
    <!-- image section -->
    <section>
        <img src="../elf/sight-seeing.png" alt="family using Trek sight seeing, enjoying the view" width="400px">
    </section>

    <!-- text section -->
    <section class="right-value">
        <article>
            <h2>Why <span>Choose</span> Us</h2>
            <p>We offer unbeatable prices and personalized experiences.</p>
        </article>

        <article class="highlight">
            <!-- each span is an icon -->
            <span></span>
            <div class="first">
                <h3>Wide Range Options</h3>
                <p>Offers a diverse selection of accommodations.</p>
            </div>
        </article>
        <article>
            <span></span>
            <div>
                <h3>Best Prices and Special Offers</h3>
                <p>Guarantee the best prices for every booking.</p>
            </div>
        </article>
        <article>
            <span></span>
            <div>
                <h3>Flexible Cancellation</h3>
                <p>User has flexibility to modify at request.</p>
            </div>
        </article>
    </section>
</div>

<style>
    .value-container {
        height: 500px;
        width: 100%;
        display: flex;
        justify-content: space-around;
        align-items: center;
        margin: auto;
        margin-top: 50px;
        background-color: hsl(0, 3%, 93%);
        font-family: Arial, Helvetica, sans-serif;
    }
     
    /* for screens smaller than 825px */
    @media (max-width: 825px) {
        .value-container {
            flex-direction: column;
            height: max-content;
            justify-content: center;
            align-items: center;
        }
    }

    .right-value {
        display: flex;
        flex-direction: column;
        gap: 10px;
    }

    .right-value > article > h2 {
        font-size: 1.8rem;
        margin-bottom: 0.7rem;
    }

    .right-value > article > h2 > span {
        color: seagreen;
    }

    .first {
        box-shadow: 10px 10px 10px lightgrey;
        padding: 2px 10px;
    }
</style>