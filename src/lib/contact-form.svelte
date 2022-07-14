<script>
    let name;
    let email;
    let phone;
    let message;

    const Contact = (e) => {
        console.log(`${name} ${phone} ${email}`)
    }
</script>

<form on:submit|preventDefault={ Contact } action="http://www.framework-y.com/scripts/php/contact-form.php" class="form-box form-ajax p-4" method="post" role="form">
    <div class="row">
        <div class="col-md-6">
            <input  bind:value={name} placeholder="name" type="text" class="form-control " required>
            { name }
        </div>
        <div class="col-md-6">
            <input  bind:value={email} placeholder="email" type="email" class="form-control " required>
        </div>
        <div class="col-md-12">
            <input bind:value={phone} placeholder="phone" type="text" class="form-control">
        </div>
    </div>
    <hr class="space xs" />
    <div class="row">
        <div class="col-md-12">
            <textarea  bind:value={message} placeholder="message" class="form-control " required></textarea>
            <hr class="space s" />
            <button class="anima-button btn-xs btn" type="submit"><i class="im-mailbox-empty"></i>Send messagge</button>
        </div>
    </div>
    <div class="success-box">
        <div class="alert alert-success">Congratulations. Your message has been sent successfully</div>
    </div>
    <div class="error-box">
        <div class="alert alert-warning">Error, please retry. Your message has not been sent</div>
    </div>
</form>