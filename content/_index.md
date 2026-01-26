+++
template = "special_page.html"
+++

<style>
.homepage {
    text-align: center;
    padding: 2rem 1rem;
}
.homepage-title {
    font-size: 3rem;
    margin-bottom: 1rem;
    line-height: 100%;
}
.homepage-subtitle {
    font-size: .9rem;
    margin-bottom: 1rem;
}

/* Responsive: smaller text on mobile */
@media (max-width: 600px) {
    .homepage-hero-title {
        font-size: 2rem;
    }
    .homepage-hero-subtitle {
        font-size: 1rem;
    }
}

</style>

<div class="homepage">
    <h1 class="homepage-title">
        Hi! I'm <span class="primary-color">J</span>annes
    </h1>
    <p class="homepage-subtitle">Currently open to research and development assignments at <a href="mailto:janneskelso@gmail.com">janneskelso@gmail.com</a>.</p>
</div>

<div style="display: flex;">
    <img style="float: right"/ src="{{ get_url(path='img/profile.jpeg') }}">
    I'm a research technologist, activist, student, and communitarian. 
</div>

