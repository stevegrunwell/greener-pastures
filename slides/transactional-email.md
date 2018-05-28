#### [![Mailgun](resources/mailgun.png)](https://www.mailgun.com/)
<!-- .element: style="font-size: 2em;" -->

<dl>
    <dt>Examples</dt>
    <dd class="fragment">Password resets</dd>
    <dd class="fragment">Admin notifications</dd>
    <dt class="fragment">Alternatives</dt>
    <dd class="fragment">Mandrill</dd>
    <dd class="fragment">Amazon SES</dd>
    <dd class="fragment">Sendgrid</dd>
</dl>

Note:

* Sendmail isn't enough, and emails need to get there
* SPF and DKIP records for verification
* Why not Mandrill?
    - MailChimp wasn't a done-deal when the first server went up
    - Probably would have been a smarter move, but I <3 Mailgun
* SES = Simple Email Service
