# Sean-Michaels-Front-Door
Landing Page for Sean Michael (Real Estate Broker)

## Contact form

The inquiry form posts to FormSubmit for delivery to Sean-Michael's email. It uses native browser validation, FormSubmit's CAPTCHA and confirmation page, and a honeypot for spam prevention. FormSubmit is configured to send a thank-you autoresponse to the visitor's required email address. FormSubmit's autoresponse requires CAPTCHA to remain enabled and does not work with AJAX submissions. Visitors should not send sensitive personal information through the form.

After deployment, submit a test inquiry from the live site. Sean-Michael must open the activation email from FormSubmit and confirm the address before delivery is enabled; check the spam folder if it does not arrive. Then submit another test using an address the tester can access, and confirm Sean receives the inquiry, reply-to works, and the tester receives the autoresponse (checking spam if needed). Changing the recipient address requires reactivation. Do not claim the form or autoresponse is working until this test succeeds.
