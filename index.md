<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <script>
            document.getElementsByTagName("html")[0].className += " js";
        </script>
        <link rel="stylesheet" href="assets/css/style.css" />
        <title>Popst FAQ</title>
    </head>
    <body>
        <header class="cd-header flex flex-column flex-center">
            <div class="text-component text-center">
                <h1>Popst FAQ</h1>
            </div>
        </header>

        <section class="cd-faq js-cd-faq container max-width-md margin-top-lg margin-bottom-lg">
            <ul class="cd-faq__categories">
                <li><a class="cd-faq__category cd-faq__category-selected truncate" href="#basics">Basics</a></li>
            </ul>
            <!-- cd-faq__categories -->

            <div class="cd-faq__items">
                <ul id="basics" class="cd-faq__group">
                    <li class="cd-faq__title"><h2>Basics</h2></li>

                    <li class="cd-faq__item">
                        <a class="cd-faq__trigger" href="#0"><span>How do I sign up?</span></a>
                        <div class="cd-faq__content">
                            <div class="text-component">
                                <p>You can signup using Facebook or email. For email, go to sign up screen, and then fill your first name, last name, email address and password.</p>
                            </div>
                        </div>
                        <!-- cd-faq__content -->
                    </li>

                    <li class="cd-faq__item">
                        <a class="cd-faq__trigger" href="#0"><span>How can I upload a story?</span></a>
                        <div class="cd-faq__content">
                            <div class="text-component">
                                <p>
                                    Click on the camera icon in the middle of the bottom tab and upload a photo or video.
                                </p>
                            </div>
                        </div>
                        <!-- cd-faq__content -->
                    </li>
                </ul>
                <!-- cd-faq__group -->
            </div>
            <!-- cd-faq__items -->

            <a href="#0" class="cd-faq__close-panel text-replace">Close</a>

            <div class="cd-faq__overlay" aria-hidden="true"></div>
        </section>
        <!-- cd-faq -->
        <script src="assets/js/util.js"></script>
        <script src="assets/js/main.js"></script>
    </body>
</html>
