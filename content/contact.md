+++
title = "Contact"
date = "2017-09-06"
sidemenu = "true"
description = "How to contact me"
+++

<form class="pure-form pure-form-stacked" method="POST" action="https://formspree.io/uli.niemann.1@gmail.com">
  <fieldset>
    <div class="pure-g">
      <div class="pure-u-1 pure-u-md-1-3">
        <label for="first-name">First Name</label>
        <input id="first-name" name="first-name" class="pure-u-23-24" type="text">
      </div>

      <div class="pure-u-1 pure-u-md-1-3">
        <label for="last-name">Last Name</label>
        <input id="last-name" name="last-name" class="pure-u-23-24" type="text">
      </div>

      <div class="pure-u-1 pure-u-md-1-3">
        <label for="email">E-Mail</label>
        <input id="email" name="email" class="pure-u-23-24" type="email" required>
      </div>

    </div>
    <fieldset class="pure-group">
      <textarea name="title" class="pure-input-1-2" placeholder="A title"></textarea>
      <textarea name="message" class="pure-input-1-2" placeholder="Your message"></textarea>
    </fieldset>
    <input type="submit" value="Send" class="pure-button pure-button-primary">
  </fieldset>
</form>
