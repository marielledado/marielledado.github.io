---
layout: page
title: Contact
permalink: /contact/
---

Get in touch if you'd like work on cool projects together, or if you just want to say hi!

After clicking the Submit button, don't forget to **tick the reCAPTCHA checkbox** in the next step--I wouldn't want to miss your message!

<form class="wj-contact" action="https://formspree.io/f/mnqongob" method="POST">
    <input type="text" name="name" placeholder="Name" required>
    <input type="text" name="email" placeholder="Email Address" required>
    <textarea type="text" name="content" rows="10" placeholder="Message" required></textarea>
    <input type="hidden" name="_next" value="<REDIRECTION LINK> ">
    <input type="hidden" name="_subject" value="New Contact Form Submission">
    <input type="text" name="_gotcha" style="display:none">
    <input type="submit" value="Submit">
</form>

<style>
form.wj-contact input[type="text"], form.wj-contact textarea[type="text"] {
    width: 100%;
    vertical-align: middle;
    margin-top: 0.25em;
    margin-bottom: 0.5em;
    padding: 0.75em;
    font-family: "Source Sans Pro", monospace, sans-serif;
    font-weight: lighter;
    border-style: solid;
    border-color: #444;
    outline-color: #2e83e6;
    border-width: 1px;
    border-radius: 3px;
    transition: box-shadow .2s ease;
}

form.wj-contact input[type="submit"] {
    outline: none;
    color: white;
    background-color: #000000;
    border-radius: 3px;
    padding: 0.5em;
    margin: 0.25em 0 0 0;
    border: 1px solid transparent;
    height: auto;
}
</style>

 Contact form created with <a href="https://formspree.io">formspree</a> 
