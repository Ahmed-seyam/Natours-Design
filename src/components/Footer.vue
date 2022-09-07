<template>
    <footer class="footer">
        <div class="footer__logo-box">
            <picture class="footer__logo">
                <source srcset='../../public/img/logo-green-small-1x.png 1x,../../public/img/logo-green-small-2x.png 2x'        media='(max-width: 37.5rem)'>
                <img srcset="../../public/img/logo-green-1x.png 1x ,../../public/img/logo-green-2x.png 2x" 
                     class="footer__logo" alt="">
            </picture>
            
        </div>
        <div class="row">
            <div class="col-1-of-2">
                <div class='footer__navigation'>
                    <ul class="footer__list">
                        <li class="footer__item">
                            <a href="" class="footer__link">Company</a>
                        </li>

                        <li class="footer__item">
                            <a href="" class="footer__link">contact us</a>
                        </li>

                        <li class="footer__item">
                            <a href="" class="footer__link">carrers</a>
                        </li>

                        <li class="footer__item">
                            <a href="" class="footer__link">privacy police</a>
                        </li>

                        <li class="footer__item">
                            <a href="" class="footer__link">Terms</a>
                        </li>


                    </ul>
                </div>
            </div>
            <div class="col-1-of-2">
                <p class="footer__copyright">
                    Built By <a href="#" class="footer__link">Ahmed Seyam</a>. Copyright &copy; Reserved For A~N Tech Company.
                </p>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
}
</script>