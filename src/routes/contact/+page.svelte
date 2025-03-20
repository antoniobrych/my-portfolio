<svelte:head>
  <title>Contact me</title>
</svelte:head>
<form action="mailto:abrych@arborcapital.com.br" method="GET">
<label for="email">Email: <input id="email" type="email" name="text_email"> </label>
<label for="subject">Subject: <input id="subject" type="text" name="text_subject"> </label>
<label for="body">Body: <textarea id="body" name="text_message"></textarea> </label>

<input type="submit" value="Submit" id="button">
</form>
