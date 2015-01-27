---
layout: page
title: contact
description: contact me
page: contact
permalink: /contact/
---

#Say hi!
<form action="//formspree.io/me@jere.me" method="POST">
  <input type="hidden" name="_next" value="//localhost/thanks.html" />
  <input type="hidden" name="_subject" value="New submission from jere.me" />
  <ul class="form-contact">
    <li class="form-input"><input class="input-field required" type="text" name="name" placeholder="Name" required  autocomplete="off"></li>
    <li class="form-input"><input class="input-field required" type="email" name="_replyto" placeholder="Email" required  autocomplete="off"></li>
    <li class="form-input--block"><textarea class="input-field required" name="message" placeholder="Message" required></textarea></li>
    <li class="form-input--block">
      <input type="text" name="_gotcha" style="display:none" />
      <input type="submit" class="btn" value="Send">
    </li>
  </ul>
</form>