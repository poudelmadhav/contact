<?php
    if (isset($_POST['ContactButton'])){
        $url = 'https://www.google.com/recaptcha/api/siteverify';
        $privatekey = "6Lc7uBIUAAAAAFI6FTQKNlBI4Aur3UlE7__gpzCl";
        $response = file_get_contents($url."?secret=".$privatekey."response=".$POST['g-recaptcha-response']."&remoteip=".$_SERVER['REMOTE_ADDR']);
        $data = json_decode($response);

        if(isset($data->success) AND $data->success==true){
            header('Location: index.php?CaptchaPass=True');
        }else{
            eader('Location: index.php?CaptchaFail=True');
        }

    }
?>

<!DOCTYPE html>
<html>
<head>
    <title>Contact | Madhav</title>
    <link rel="stylesheet" type="text/css" href="css/style.css">
    <script src='https://www.google.com/recaptcha/api.js'></script>
</head>
<body>

<div class="Header">
    <h1>Contact Me</h1>
    <?php if(isset($_GET['CaptchaPass'])) { ?>
    <div class="MP">Message Sent</div>
    <?php } ?>
    <?php if(isset($_GET['CaptchaFail'])) { ?>
    <div class="MP">Please verify that you are not a robot.</div>
    <?php } ?>
</div>
    <form action="https://formspree.io/poudelmadhav78@gmail.com" method="POST" id="contactForm" name="contactForm">
                    <fieldset>

                  <div>
                           <label for="contactName">Name <span class="required">*</span></label>
                           <input type="text" value="" size="35" id="contactName" name="Name" placeholder="Your name" required aria-required="true">
                  </div>

                  <div>
                           <label for="contactEmail">Email <span class="required">*</span></label>
                           <input type="email" value="" size="35" id="Email" name="Email" placeholder="Your email" required aria-required="true">
                  </div>
        
          <div>
                           <label for="website">Website</label>
                           <input type="url" name="Website" id="contactWebsite" value="" class="url" placeholder="Optional">
                    
          </div>
                  <div>
                           <input type="hidden" name="_subject" id="contactSubject" value="[Madhav Paudel] Contact" />
        </div>

                  <div>
                     <label for="contactMessage">Message <span class="required">*</span></label>
                     <textarea cols="50" rows="15" id="contactMessage" name="Message" placeholder="Your comment or message" required aria-required="true"></textarea>
                  </div>
                  <div class="MP">
                  <div class="g-recaptcha" data-sitekey="6Lc7uBIUAAAAAJNnsjxj43mjde-QU5TsG45EFMBy"></div>
                  </div>

                  <div>
                     <button class="submit" type="submit" id="ContactButton">Submit</button>
            <input type="hidden" name="_next" value="thankyou.html" />
                  </div>

                    </fieldset>
                   </form> <!-- Form End -->
</body>
</html>
