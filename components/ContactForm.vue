<template>
<section class="section">
<div class="container">
<div class="content">
<h2>
<font style="vertical-align: inherit;">
<font style="vertical-align: inherit;">お問い合わせ</font></font>
</h2>
<br>

<form name="contact" method="post" action="/contact/thanks/" 
data-netlify="true" data-netlify-honeypot="bot-field">
<input type="hidden" name="form-name" value="contact">

<div hidden="">
<label>
<font style="vertical-align: inherit;">
<font style="vertical-align: inherit;">これを記入しないでください：</font></font> 
<input name="bot-field">
</label>
</div>

<div class="field">
<label class="label" for="name">
<font style="vertical-align: inherit;">
<font style="vertical-align: inherit;">あなたの名前</font></font>
</label>
<div class="control">
<input class="input" type="text" name="name" id="name" required="">
</div>
</div>

<div class="field">
<label class="label" for="email"><font style="vertical-align: inherit;">
<font style="vertical-align: inherit;">E-メール</font></font>
</label>
<div class="control">
<input class="input" type="email" name="email" id="email" required="">
</div></div>

<div class="field">
<label class="label" for="message">
<font style="vertical-align: inherit;">
<font style="vertical-align: inherit;">メッセージ</font></font>
</label>
<div class="control">
<textarea class="textarea" name="message" id="message" required=""></textarea>
</div></div>

<div class="field">
<button class="button is-link" type="submit"><font style="vertical-align: inherit;">
<font style="vertical-align: inherit;">送信する</font></font>
</button>
</div>
</form>
</div></div>
</section>
</template>
