   
  
   
    <form class="order-form" action="#">'
    <h2 class="form-title">Leave your contacts and we will call you back</h2>
    <label class="order-form-field-lable" for="user-name">Name</label>
    <input class="form-input"
      type="text"
      name="user-name"
      id="user-name"
      pattern="[a-zA-Z]"
      required
      autofocus
    />
    <label class="order-form-field-lable" for="phone">Phone</label>
    <input class="form-input" type="tel" name="phone" id="phone"
    required
    />

    <label class="order-form-field-lable" for="e-mail">E-Mail</label>
    <input class="form-input" type="email" name="" id="e-mail">


    <label  class="order-form-comment"  for="comment-text">Comment</label>
    <textarea  class="form-textarea"
     name="comment-text" id="comment-text" placeholder="Text input" rows=""></textarea>

<input  class="form-input" type="checkbox" name="chechbox"> I accept the terms
and conditions of the

<a class="checkbox-link" href="#">Privacy Policy</a>

<button class="form-btn-submit"
  type="submit">Send</button>

  </form>

.form-title { padding-top: 72px; padding-bottom: 16px;

font-size: 16px; line-height: 1.5; letter-spacing: 0.02em; text-align: center;
color: #2e2f42; } .order-form { padding-top: 72px; display: flex;
flex-direction: column; width: 408px; min-height: 584px; box-shadow: 0 1px 1px 0
rgba(0, 0, 0, 0.14), 0 1px 3px 0 rgba(0, 0, 0, 0.12), 0 2px 1px 0 rgba(0, 0, 0,
0.2); background: #fcfcfc; margin-left: auto; margin-right: auto; border: 4px
solid #31d0aa; border-radius: 4px; padding-left: 24px; padding-right: 24px;
padding-bottom: ;}

.order-form-field-lable { display: block; font-size: 12px; margin-bottom: 4px;
line-height: 1.16 ; letter-spacing: 0.04em; color: #8e8f99; }

/_.form-textarea { width: ; }_/

.form-input { border-radius: 4px; border: 1px solid #8e8f99; }

.order-form-comment { display: flex; width: 100%; padding: 15px; resize: none;

}

.checkbox-link { text-decoration: underline; }

.form-btn-submit {

display: flex; align-items: center; justify-content: center; font-weight: 500;
font-size: 16px; line-height: 1.5; letter-spacing: 0.04em; color: #fff;
box-shadow: 0 4px 4px 0 rgba(0, 0, 0, 0.15); background: #4d5ae5; border-radius:
4px; padding: 16px 32px; border: none; min-width: 169px; min-height: 56px;

text-align: center; }

form:focus-within { border-color: blue; }
