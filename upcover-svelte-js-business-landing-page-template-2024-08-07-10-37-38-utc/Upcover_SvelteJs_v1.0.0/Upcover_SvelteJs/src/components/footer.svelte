<script>
    import logoLight from '../assets/images/logo-light.png'
    import {ShoppingCartIcon , DribbbleIcon , LinkedinIcon , FacebookIcon , InstagramIcon , TwitterIcon , MailIcon } from 'svelte-feather-icons'

</script>
<footer class="footer bg-dark-footer relative text-gray-200 dark:text-gray-200">
    <div class="py-[30px] px-0 border-t border-slate-800">
        <div class="container relative text-center">
            <div class="grid lg:grid-cols-12 md:grid-cols-3 grid-cols-1 items-center">
                <div class="lg:col-span-3 md:text-start text-center">
                    <a href="/#" class="text-[22px] focus:outline-none">
                        <img src={logoLight} class="mx-auto md:me-auto md:ms-0" alt=""/>
                    </a>
                </div>

                <div class="lg:col-span-5 text-center mt-6 md:mt-0">
                    <p class="mb-0">© {new Date().getFullYear()} Upcover. Design & Develop with <i class="mdi mdi-heart text-red-600"></i> by <a href="https://shreethemes.in/" target="_blank" class="text-reset">Shreethemes</a>.</p>
                </div>

                <ul class="lg:col-span-4 list-none md:text-end text-center mt-6 md:mt-0">
                    <li class="inline"><a href="https://1.envato.market/upcover-svelte" target="_blank" class="size-8 inline-flex justify-center items-center border border-gray-800 rounded-md hover:border-teal-500 dark:hover:border-teal-500 hover:bg-teal-500 dark:hover:bg-teal-500"><ShoppingCartIcon data-feather="shopping-cart" class="size-4 align-middle" title="Buy Now"/></a></li>
                    <li class="inline"><a href="https://dribbble.com/shreethemes" target="_blank" class="size-8 inline-flex justify-center items-center border border-gray-800 rounded-md hover:border-teal-500 dark:hover:border-teal-500 hover:bg-teal-500 dark:hover:bg-teal-500"><DribbbleIcon class="size-4 align-middle" title="dribbble"/></a></li>
                    <li class="inline"><a href="http://linkedin.com/company/shreethemes" target="_blank" class="size-8 inline-flex justify-center items-center border border-gray-800 rounded-md hover:border-teal-500 dark:hover:border-teal-500 hover:bg-teal-500 dark:hover:bg-teal-500"><LinkedinIcon class="size-4 align-middle" title="Linkedin"/></a></li>
                    <li class="inline"><a href="https://www.facebook.com/shreethemes" target="_blank" class="size-8 inline-flex justify-center items-center border border-gray-800 rounded-md hover:border-teal-500 dark:hover:border-teal-500 hover:bg-teal-500 dark:hover:bg-teal-500"><FacebookIcon class="size-4 align-middle" title="instagram"/></a></li>
                    <li class="inline"><a href="https://www.instagram.com/shreethemes/" target="_blank" class="size-8 inline-flex justify-center items-center border border-gray-800 rounded-md hover:border-teal-500 dark:hover:border-teal-500 hover:bg-teal-500 dark:hover:bg-teal-500"><InstagramIcon class="size-4 align-middle" title="instagram"/></a></li>
                    <li class="inline"><a href="https://twitter.com/shreethemes" target="_blank" class="size-8 inline-flex justify-center items-center border border-gray-800 rounded-md hover:border-teal-500 dark:hover:border-teal-500 hover:bg-teal-500 dark:hover:bg-teal-500"><TwitterIcon class="size-4 align-middle" title="twitter"/></a></li>
                    <li class="inline"><a href="mailto:support@shreethemes.in" class="size-8 inline-flex justify-center items-center border border-gray-800 rounded-md hover:border-teal-500 dark:hover:border-teal-500 hover:bg-teal-500 dark:hover:bg-teal-500"><MailIcon class="size-4 align-middle" title="email"/></a></li>
                </ul>
            </div>
        </div>
    </div>
</footer>