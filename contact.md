---
layout: default
title: contact
permalink: /contact/
---

<script src="https://www.google.com/recaptcha/api.js" async defer></script>
<script>function onSubmit(token) {document.getElementById("demo-form").submit()}</script>
<form id='demo-form' action="?" accept-charset="UTF-8" action="https://getform.io/f/cdee5a80-69df-482c-a98c-21857651c84a" method="POST" enctype="multipart/form-data" target="_blank">
      <div class="form-group">
        <label for="InputEmail" required="required">Email address</label>
        <br>
        <input type="email" name="email" class="form-control" id="InputEmail" aria-describedby="emailHelp" placeholder="Your email address">
      </div>
      <div class="form-group">
        <label for="exampleInputName">Name</label>
        <br>
        <input type="text" name="name" class="form-control" id="exampleInputName" placeholder="Enter your name" required="required">
      </div>
      <div class="form-group">
        <label for="Input" required="required">Subject</label>
        <br>
        <textarea type="text" name="input" class="form-control" id="Input" aria-describedby="emailHelp" placeholder="Subject" required="required"></textarea>
      </div>
      <br>
      <button  type="submit" class="g-recaptcha" data-sitekey="6Ld72igbAAAAAC48ufZ8QvQbcdr6ry2G_748r5rh" data-callback='onSubmit'>Submit</button>
    </form>