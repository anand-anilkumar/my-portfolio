<template>
    <div class="contact-block">
        <h3>Contact Us</h3>
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <p>anandanilab@gmail.com</p>
                    <p>+918593031054</p>
                    <a href="https://github.com/anand-anilkumar" rel="nofollow"
                       target="_blank"><i class="fa fa-github-square"></i></a>
                    <a href="https://www.linkedin.com/in/anand-anilkumar/" rel="nofollow"
                       target="_blank"><i class="fa fa-linkedin-square"></i></a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

  export default {
    name: 'Contact',
  }
</script>

<style scoped>
    @import '../assets/css/icons.css';

    .contact-block {
        min-height: 100vh;
    }

    .contact-block .row {
        padding: 100px 0 0 0;
    }

    .contact-block p {
        color: #aaa;
        font-family: 'PT Sans Caption', sans-serif;
        font-size: 48px;
    }

    .contact-block p a {
        text-decoration: none;
        color: #aaa;
    }

    .contact-block i {
        color: #aaa;
        margin: 20px 20px 0 0;
        font-size: 48px;
        transition: all .35s ease-in-out;
    }
    .contact-block h3 {
        font-size: 50px;
    }
    .contact-block i:hover {
        color: #fff;
        transition: all .35s ease-in-out;
    }

    @media screen and (max-width: 768px) {
        .contact-block .row {
            padding: 50px 0;
            text-align: center;
        }

        .contact-block p {
            font-size: 24px;
        }

        .contact-block a:last-child i {
            margin-right: 0;
        }
    }
</style>