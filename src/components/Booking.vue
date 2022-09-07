<template>
    <section class="section-bookings" id='section-book'>
        <div class="row">
            <div class="book">
                <div class="book__form">
                    <form class="form">
                        <div class=" u-margin-bottom-meduim">
                            <h2 class="heading--secondary">
                                Start Booking Now
                            </h2>
                        </div>
                        <div class="form__group">
                            <input id='name' type="text" class="form__input" placeholder="Full Name" required>
                            <label for="name" class="form__label">Full Name</label>
                        </div>
                        <div class="form__group">
                            <input id='email' type="email" class="form__input" placeholder="Type Your Email" required>
                            <label for="email" class="form__label">Email Adress</label>
                        </div>

                        <div class="form__group">
                            <div class="form__radio-group">
                                <input type="radio" id='small' class="form__radio-input" name='size'>
                                <label for="small" class="form__radio-label">
                                <span class="form__radio-button"></span>
                                small tour group</label>
                            </div>

                            <div class="form__radio-group">
                                <input type="radio" id='large' class="form__radio-input" name='size'>
                                <label for="large" class="form__radio-label">
                                <span class="form__radio-button"></span>
                                large tour group</label>
                            </div>


                        </div>
                        <div class="form__group">
                            <button class="btn btn--green btn--animated">next step &rarr;</button>
                        </div>

                    </form>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {

}
</script>