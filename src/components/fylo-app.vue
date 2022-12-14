<template>
    <div class="app-container">
        <div class="hero">
            <img src="../assets/imgs/main1.png" alt="">
            <h2>All your files in one secure location, accessible anywhere.</h2>
            <p>Fylo stores all your most important files in one secure location. Access them wherever you need, share
                and collaborate with friends family, and co-workers.</p>
            <button>Get Started</button>
        </div>

        <fylo-info />

        <div class="secondary-hero">
            <img src="../assets/imgs/main2.png" alt="">
            <div class="stay-productive">
                <h2>Stay productive, wherever you are</h2>
                <p>Never let location be an issue when accessing your files. Fylo has you covered for all of your file
                    storage needs.</p>
                <p>Securely share files and folders with friends, family and colleagues for live collaboration. No email
                    attachments required.</p>
                <a href="#">See how fylo works</a>
            </div>
        </div>

        <div class="review-list">
            <div class="review-preview">
                <img class="apostrophes" src="../assets/imgs/bg-quotes.png" alt="">
                <p>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team
                    has become a well-oiled collaboration machine.</p>
                <div class="user-container">
                    <img src="../assets/imgs/Satish.png" alt="">
                    <div class="">
                        <h4>Satish Patel</h4>
                        <p>Founder & CEO, Huddle</p>
                    </div>
                </div>
            </div>
            <div class="review-preview">
                <p>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team
                    has become a well-oiled collaboration machine.</p>
                <div class="user-container">
                    <img src="../assets/imgs/Bruce.png" alt="">
                    <div class="">
                        <h4>Bruce McKenzie</h4>
                        <p>Founder & CEO, Huddle</p>
                    </div>
                </div>
            </div>
            <div class="review-preview">
                <p>Fylo has improved our team productivity by an order of magnitude. Since making the switch our team
                    has become a well-oiled collaboration machine.</p>
                <div class="user-container">
                    <img src="../assets/imgs/iva.png" alt="">
                    <div class="">
                        <h4>Iva Boyd</h4>
                        <p>Founder & CEO, Huddle</p>
                    </div>
                </div>
            </div>
        </div>

        <early-access />

    </div>
</template>

<script>
import fyloInfo from './fylo-info.vue';
import reviewPreview from './review-preview.vue';
import earlyAccess from './early-access.vue';

export default {
    components: {
        fyloInfo,
        reviewPreview,
        earlyAccess
    }
}
</script>