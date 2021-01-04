---
layout: default
title: contact
permalink: /contact/
---


<script src="https://www.google.com/recaptcha/api.js" async defer></script>
<script src="{{ base.url | prepend: site.url }}/assets/captcha.js"></script>
<form accept-charset="UTF-8" action="https://getform.io/f/cdee5a80-69df-482c-a98c-21857651c84a" method="POST" enctype="multipart/form-data" target="_blank">
      <div class="form-group">
        <label for="InputEmail" required="required">Email address</label>
        <br>
        <input type="email" name="email" class="form-control" id="InputEmail" aria-describedby="emailHelp" placeholder="Your email address here so I can get back to you">
      </div>
      <div class="form-group">
        <label for="exampleInputName">Name</label>
        <br>
        <input type="text" name="name" class="form-control" id="exampleInputName" placeholder="Enter your name" required="required">
      </div>
      <div class="form-group">
        <label for="Input" required="required">Write things here (or don't idk)</label>
        <br>
        <input type="text" name="input" class="form-control" id="Input" aria-describedby="emailHelp" placeholder="Reason you are contacting me">
        <!--<div class="g-recaptcha" data-sitekey="6Ld_niAaAAAAAJsNgTqNi0TIwfH6y8WKFX6Ic49X"></div>-->
      </div>
      <br>
      <!--<button type="submit" class="btn btn-primary">Submit</button>-->
      <button class="g-recaptcha" type="submit" data-sitekey="6LfOpiAaAAAAACxkWlByx6yRTsrgJO08n3bmGgGP" data-callback='onSubmit'>Submit</button>

    </form>