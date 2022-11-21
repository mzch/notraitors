---
Title: 連絡
date: "2022-11-03"
drafts: false
comment: false
---

何か言伝があれば以下の連絡フォームからどうぞ。

<script src="https://www.google.com/recaptcha/api.js?hl=ja" async defer></script>
<p style="margin-top:3em;">
<form action="https://submit-form.com/4QdVEopO" method="POST"  target="_blank">
  <p>
  <label for="name" style="font-size:small;">お名前</label>
  <input type="text" id="name" name="name" placeholder="" required="" style="background-color:#f0f0f0; width:100%" />
  </p>
  <p>
  <label for="email" style="font-size:small;">メール</label>
  <input type="email" id="email" name="email" placeholder="example@example.jp" required="" style="background-color:#f0f0f0; width:100%;" />
  <input type="email" id="replayto" name="replayto" style="display: none;" />
  </p>
  <p>
  <label for="message" style="font-size:small">メッセージ</label>
  <textarea
    id="message"
    name="message"
    placeholder="何でもお書き下さい。"
    required="true"
    style="background-color:#f0f0f0; width:100%; height:8em;"
  ></textarea></p>
  <p>
  <div
    class="g-recaptcha"
    data-sitekey="6LdfetIiAAAAAPQg1hBLZa1d7aTHWUVmxH5e9Hma"
    data-callback="callback"
  ></div></p>
  <button type="submit" id="submit-button" style="padding:0px 20px 10px 20px !important; color:white; background-color:gray;" disabled>送信</button>
</form>
</p>

<script type="text/javascript">
      function callback() {
        const submitButton = document.getElementById("submit-button");
        submitButton.removeAttribute("disabled");
      }
</script>
