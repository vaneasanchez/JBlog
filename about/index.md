---
layout: page
title: About the Theme
tags: [about, Jekyll, theme, JBlog]
date: 2016-03-21
---

<!-- Latest Post Preview Start -->
  
 <section id="{{ page.section-type }}" class="container content-section text-center">
     <div class="row">
       <div class="col-md-10 col-md-offset-1">
       </div>
     </div>   
 </section>

<!-- Latest Post Preview End -->

 <!doctype html>
<html lang="en">

<body>
  <h2 class="content-head is-center">Request A Custom Woodburning!</h2>

<!-- START HERE -->
  <link rel="stylesheet" href="https://yui.yahooapis.com/pure/0.6.0/pure-min.css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
    <!-- Style The Contact Form How Ever You Prefer -->
  <link rel="stylesheet" href="/css/form.css">
  
  <form id="gform" method="POST" class="container"
  action="https://script.google.com/macros/s/AKfycbyePyppGycT3iwxNPE7kv6o4SCKXDXLR5H8lJDOUd3dgexQC7e9/exec">
    <!-- change the form action to your script url -->

    <fieldset class="container">
      <label for="name">Name: </label>
      <input id="name" name="name" placeholder="name" />
    </fieldset>

    <fieldset class="container">
      <label for="message">Message: </label>
      <textarea id="message" name="message" rows="10"
      placeholder="describe your desired piece..."></textarea>
    </fieldset>

    <fieldset class="container">
      <label for="email">Your Email Address:</label>
      <input id="email" name="email" type="email" value=""
      required placeholder="your.name@email.com"/>
      <span id="email-invalid" style="visibility:hidden">
        Must be a valid email address</span>
    </fieldset>

    <fieldset class="container">
      <label for="color">Phone Number (optional):</label>
      <input id="color" name="color" placeholder="" />
    </fieldset>

    <button class="button-success pure-button button-xlarge">
      <i class="fa fa-paper-plane"></i>&nbsp;Send</button>

  </form>

  <!-- Customise the Thankyou Message People See when they submit the form: -->
  <div style="display:none;" id="thankyou_message">
    <h2 class="content-head is-center">Thanks for contacting me!
      I will get back to you soon!</h2>
  </div>

  <!-- Submit the Form to Google Using "AJAX" -->
  <script data-cfasync="false" type="text/javascript"
  src="https://cdn.rawgit.com/dwyl/html-form-send-email-via-google-script-without-server/master/form-submission-handler.js"></script>
  <!-- <script data-cfasync="false" type="text/javascript"
  src="/form-submission-handler.js"></script> -->
<!-- END -->

</body>
</html>
