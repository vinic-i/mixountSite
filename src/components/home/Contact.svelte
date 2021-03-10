<script>
    import {
        city,
        country,
        address,
        contactEmail,
        phoneNumber,
        phoneNumber2,
        infoEmail,
    } from "../../config";
</script>

<section id="contact" class="contact">
    <div class="container" data-aos="fade-up">
        <header class="section-header">
            <h2>Contato</h2>
            <p>Entre em Contato</p>
        </header>

        <div class="row gy-4">
            <div class="col-lg-6">
                <div class="row gy-4">
                    <div class="col-md-6">
                        <div class="info-box">
                            <i class="bi bi-geo-alt" />
                            <h3>Endereço</h3>
                            <p>{address},<br />{city}</p>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="info-box">
                            <i class="bi bi-telephone" />
                            <h3>Ligue para</h3>
                            <p>{phoneNumber}<br />{phoneNumber2}</p>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="info-box">
                            <i class="bi bi-envelope" />
                            <h3>Email</h3>
                            <p>{infoEmail}<br />{contactEmail}</p>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="info-box">
                            <i class="bi bi-clock" />
                            <h3>Suporte</h3>
                            <p>Segunda - Sexta<br />9:00AM - 05:00PM</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="col-lg-6">
                <form
                    action="forms/contact.php"
                    method="post"
                    class="php-email-form"
                >
                    <div class="row gy-4">
                        <div class="col-md-6">
                            <input
                                type="text"
                                name="name"
                                class="form-control"
                                placeholder="Seu Nome"
                                required
                            />
                        </div>

                        <div class="col-md-6 ">
                            <input
                                type="email"
                                class="form-control"
                                name="email"
                                placeholder="Seu Email"
                                required
                            />
                        </div>

                        <div class="col-md-12">
                            <input
                                type="text"
                                class="form-control"
                                name="subject"
                                placeholder="Assunto"
                                required
                            />
                        </div>

                        <div class="col-md-12">
                            <textarea
                                class="form-control"
                                name="message"
                                rows="6"
                                placeholder="Mensagem"
                                required
                            />
                        </div>

                        <div class="col-md-12 text-center">
                            <div class="loading">Loading</div>
                            <div class="error-message" />
                            <div class="sent-message">
                               Sua mensagem foi enviada. Muito obrigado!
                            </div>

                            <button type="submit">Enviar mensagem</button>
                        </div>
                    </div>
                </form>
            </div>
        </div>
    </div>
</section>
