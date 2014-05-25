---
layout: page
title: Volunteer
permalink: /volunteer/
show_in_nav: true
---

Join our list of volunteers. We'll reach out to you to help with our next event/program.

<form role="form" action="https://www.salesforce.com/servlet/servlet.WebToLead?encoding=UTF-8" method="POST">


<input type="hidden" name="oid" value="00DG0000000lOCx">
<input type="hidden" name="retURL" value="{{ site.url }}{{ site.baseurl }}/volunteer-thanks/">

<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: These fields are optional debugging elements. Please uncomment    -->
<!--  these lines if you wish to test in debug mode.                          -->
<!--  <input type="hidden" name="debug" value=1>                              -->
<!--  <input type="hidden" name="debugEmail"                                  -->
<!--  value="clinton@blackburnfoundation.org">                                -->
<!--  ----------------------------------------------------------------------  -->

<div class="form-group">
  <label for="first_name">First Name</label>
  <input class="form-control" id="first_name" maxlength="40" name="first_name" size="20" type="text" />
</div>

<div class="form-group">
  <label for="last_name">Last Name</label>
  <input class="form-control" id="last_name" maxlength="80" name="last_name" size="20" type="text" />
</div>

<div class="form-group">
  <label for="email">Email</label>
  <input class="form-control" id="email" maxlength="80" name="email" size="20" type="text" />
</div>

<div class="form-group">
  <label for="phone">Phone</label>
  <input class="form-control" id="phone" maxlength="40" name="phone" size="20" type="text" />
</div>

<div class="form-group">
  <label for="city">City</label>
  <input class="form-control" id="city" maxlength="40" name="city" size="20" type="text" />
</div>

<div class="form-group">
  <label for="state">State/Province</label>
  <input class="form-control" id="state" maxlength="20" name="state" size="20" type="text" />
</div>

  <button type="submit" class="btn btn-default">Submit</button>


</form>
