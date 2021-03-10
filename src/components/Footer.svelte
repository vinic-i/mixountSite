<script>
    import {city, country, address, contactEmail, phoneNumber} from "../config"
</script>

<footer id="footer" class="footer">
    <div class="footer-newsletter">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-lg-12 text-center">
                    <h4>Inscreva-se para novidades!</h4>
                    <p>
                        Fique por dentro de todas as atualizações e melhorias no sitema da Mixount! 
                    </p>
                </div>
                <div class="col-lg-6">
                    <form action="" method="post">
                        <input type="email" name="email" /><input
                            type="submit"
                            value="Subscribe"
                        />
                    </form>
                </div>
            </div>
        </div>
    </div>

    <div class="footer-top">
        <div class="container">
            <div class="row gy-4">
                <div class="col-lg-5 col-md-12 footer-info">
                    <a href="index.html" class="logo d-flex align-items-center">
                        <img src="assets/img/logo.png" alt="" />
                        <span>Mixou NT</span>
                    </a>
                    <p>
                        Desenvolvendo soluções de negócios através da tecnogolia. </p>
                    <div class="social-links mt-3">
                        <a href="." class="twitter"
                            ><i class="bi bi-twitter" /></a
                        >
                        <a href="." class="facebook"
                            ><i class="bi bi-facebook" /></a
                        >
                        <a href="." class="instagram"
                            ><i class="bi bi-instagram bx bxl-instagram" /></a
                        >
                        <a href="." class="linkedin"
                            ><i class="bi bi-linkedin bx bxl-linkedin" /></a
                        >
                    </div>
                </div>

                <div class="col-lg-2 col-6 footer-links">
                    <h4>Mixou NT</h4>
                    <ul>
                        <li>
                            <i class="bi bi-chevron-right" />
                            <a href=".">Início</a>
                        </li>
                        <li>
                            <i class="bi bi-chevron-right" />
                            <a href=".">Sobre nós</a>
                        </li>
                        <li>
                            <i class="bi bi-chevron-right" />
                            <a href=".">Serviços</a>
                        </li>
                        <li>
                            <i class="bi bi-chevron-right" />
                            <a href=".">Termos de serviço</a>
                        </li>
                        <li>
                            <i class="bi bi-chevron-right" />
                            <a href=".">Política de privacidade</a>
                        </li>
                    </ul>
                </div>

                <div class="col-lg-2 col-6 footer-links">
                    <h4>Nosso serviços</h4>
                    <ul>
                        <li>
                            <i class="bi bi-chevron-right" />
                            <a href=".">Mixou Escola</a>
                        </li>
                        <li>
                            <i class="bi bi-chevron-right" />
                            <a href=".">Pessoas como serviço</a>
                        </li>
                        <li>
                            <i class="bi bi-chevron-right" />
                            <a href=".">Web Design</a>
                        </li>
                        <!-- <li>
                            <i class="bi bi-chevron-right" />
                            <a href=".">Marketing</a>
                        </li>
                        <li>
                            <i class="bi bi-chevron-right" />
                            <a href=".">Graphic Design</a>
                        </li> -->
                    </ul>
                </div>

                <div
                    class="col-lg-3 col-md-12 footer-contact text-center text-md-start"
                >
                    <h4>Contact Us</h4>
                    <p>
                        {address} <br />{city}<br />{country} <br /><br />
                        <strong>Phone:</strong> {phoneNumber}<br />
                        <strong>Email:</strong> {contactEmail}<br />
                    </p>
                </div>
            </div>
        </div>
    </div>

    <div class="container">
        <div class="copyright">
            &copy; Copyright <strong><span>Mixou NT</span></strong>. All Rights
            Reserved
        </div>
        <div class="credits">
            <!-- All the links in the footer should remain intact. -->
            <!-- You can delete the links only if you purchased the pro version. -->
            <!-- Licensing information: https://bootstrapmade.com/license/ -->
            <!-- Purchase the pro version with working PHP/AJAX contact form: https://bootstrapmade.com/flexstart-bootstrap-startup-template/ -->
            Designed by Mixou NT
        </div>
    </div>
</footer>
