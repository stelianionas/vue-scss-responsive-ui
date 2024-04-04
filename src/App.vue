<script setup>
    import Hamburger from './components/hamburger.vue';
</script>

<template>
    <div class="root">
        <header>
            <nav>
                <span>Logo</span>
                <div class="header-links">
                    <span>Home</span>
                    <span>Tourism</span>
                    <span>Medical Tourism</span>
                    <span>Contacts</span>
                </div>
                <img src="./assets/images/globe.svg" alt="Globe" ondragstart="return false;">
                <div class="hamburger">
                    <Hamburger />
                </div>
            </nav>
        </header>
        <main>
            <div class="full-main-container">
                <div>
                    <div class="title-and-review">
                        <h1>Africa - Amazing African Safari</h1>
                        <div class="stars">
                            <img class="star" src="./assets/images/star.svg" alt="Star">
                            <img class="star" src="./assets/images/star.svg" alt="Star">
                            <img class="star" src="./assets/images/star.svg" alt="Star">
                            <img class="star" src="./assets/images/star.svg" alt="Star">
                            <img class="star" src="./assets/images/star.svg" alt="Star">
                        </div>
                        <p>9 Nights / Full Board / Airplane</p>
                    </div>
                    <div class="image-grid-container">
                        <img id="africa1-main" src="./assets/images/africa1.png" alt="Africa1">
                        <div class="image-grid">
                            <img src="./assets/images/africa2.png" alt="Africa2">
                            <img src="./assets/images/africa3.png" alt="Africa3">
                            <img src="./assets/images/africa4.png" alt="Africa4">
                            <img src="./assets/images/africa5.png" alt="Africa5">
                        </div>
                    </div>
                </div>
                <div class="second-main-container">
                    <div class="details-container">
                        <h2>Detail</h2>
                        <p>Leave Your Guidebooks At Home And Dive Into The Local Cultures That Make Each Destination So
                            Special. We’ll Connect You With Our Exclusive Experiences. Each Trip Is Carefully Crafted To
                            Let Enjoy Your Vacation. <br><br>A Wonderful Serenity Has Taken Possession Of My Entire
                            Soul, Like These Sweet Mornings Of Spring Which I Enjoy With My Whole Heart. I Am Alone, And
                            Feel The Charm Of Existence In This Spot, Which Was Created For The Bliss Of Souls Like
                            Mine. I Am So Happy, My Dear Friend, So Absorbed In The Exquisite Sense Of Mere Tranquil
                            Existence, That I Neglect My Talents.</p>
                        <h2>Price Includes</h2>
                        <ul>
                            <li><span>✓ </span>9 Nights</li>
                            <li><span>✓ </span>Departure from Chișinău</li>
                            <li><span>✓ </span>Full Board</li>
                            <li><span>✓ </span>Airplane</li>
                        </ul>
                    </div>
                    <div class="buttons-and-booking-info">
                        <div class="detail-buttons">
                            <button id="pricebtn">From <span>$100</span></button>
                            <button id="contactbtn">Contact Us</button>
                        </div>
                        <div class="booking-info">
                            <div class="book-with-confidence">
                                <h2>Book With Confidence</h2>
                            </div>
                            <ul>
                                <li>
                                    <img src="./assets/images/thumbsup.svg" alt="Thumbs Up">
                                    <span>No-hassle best price guarantee</span>
                                </li>
                                <li>
                                    <img src="./assets/images/phone.svg" alt="Phone">
                                    <span>Customer care available 24/7</span>
                                </li>
                                <li>
                                    <img src="./assets/images/bluestar.svg" alt="Blue Star">
                                    <span>Hand-picked Tours & Activities</span>
                                </li>
                                <li>
                                    <img src="./assets/images/lifering.svg" alt="Life Ring">
                                    <span>Free Travel Insurance</span>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="third-main-container">
                    <h2>Related Tours</h2>
                    <div class="tours">
                        <div class="tour">
                            <img src="./assets/images/africa6.png" alt="Africa6">
                            <div class="tour-details">
                                <h3>Africa - Amazing African Safari</h3>
                                <div>
                                    <img class="star" src="./assets/images/star.svg" alt="Star">
                                    <img class="star" src="./assets/images/star.svg" alt="Star">
                                    <img class="star" src="./assets/images/star.svg" alt="Star">
                                    <img class="star" src="./assets/images/star.svg" alt="Star">
                                    <img class="star" src="./assets/images/star.svg" alt="Star">
                                </div>
                                <p>From <span>$100</span></p>
                            </div>
                        </div>
                        <div class="tour">
                            <img src="./assets/images/africa6.png" alt="Africa 6">
                            <div class="tour-details">
                                <h3>Africa - Amazing African Safari</h3>
                                <div>
                                    <img class="star" src="./assets/images/star.svg" alt="Star">
                                    <img class="star" src="./assets/images/star.svg" alt="Star">
                                    <img class="star" src="./assets/images/star.svg" alt="Star">
                                    <img class="star" src="./assets/images/star.svg" alt="Star">
                                    <img class="star" src="./assets/images/star.svg" alt="Star">
                                </div>
                                <p>From <span>$100</span></p>
                            </div>
                        </div>
                        <div class="tour">
                            <img src="./assets/images/africa6.png" alt="Africa 6">
                            <div class="tour-details">
                                <h3>Africa - Amazing African Safari</h3>
                                <div>
                                    <img class="star" src="./assets/images/star.svg" alt="Star">
                                    <img class="star" src="./assets/images/star.svg" alt="Star">
                                    <img class="star" src="./assets/images/star.svg" alt="Star">
                                    <img class="star" src="./assets/images/star.svg" alt="Star">
                                    <img class="star" src="./assets/images/star.svg" alt="Star">
                                </div>
                                <p>From <span>$100</span></p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </main>
        <footer>
            <h1>Logo</h1>
            <div class="footer-main-container">
                <div class="list-and-socials">
                    <ul>
                        <li>Home</li>
                        <li>Tourism</li>
                        <li>Medical Tourism</li>
                        <li>Contacts</li>
                    </ul>
                    <div class="socials">
                        <img src="./assets/images/instagram.svg" alt="Instagram" ondragstart="return false;">
                        <img src="./assets/images/facebook.svg" alt="Facebook" ondragstart="return false;">
                        <img src="./assets/images/telegram.png" alt="Telegram" ondragstart="return false;">
                        <img src="./assets/images/tiktok.svg" alt="TikTok" ondragstart="return false;">
                    </div>
                </div>
                <div class="social-imgs">
                    <h4>Instagram</h4>
                    <div>
                        <img src="./assets/images/footerph.png" alt="Footer Placeholder">
                        <img src="./assets/images/footerph.png" alt="Footer Placeholder">
                        <img src="./assets/images/footerph.png" alt="Footer Placeholder">
                        <img src="./assets/images/footerph.png" alt="Footer Placeholder">
                        <img src="./assets/images/footerph.png" alt="Footer Placeholder">
                        <img src="./assets/images/footerph.png" alt="Footer Placeholder">
                    </div>
                </div>
                <div class="social-imgs">
                    <h4>Tik-Tok</h4>
                    <div>
                        <img src="./assets/images/footerph.png" alt="Footer Placeholder">
                        <img src="./assets/images/footerph.png" alt="Footer Placeholder">
                        <img src="./assets/images/footerph.png" alt="Footer Placeholder">
                        <img src="./assets/images/footerph.png" alt="Footer Placeholder">
                        <img src="./assets/images/footerph.png" alt="Footer Placeholder">
                        <img src="./assets/images/footerph.png" alt="Footer Placeholder">
                    </div>
                </div>
            </div>
            <p>© 2024 FainTravel.md | All Rights Reserved</p>
        </footer>
    </div>
</template>