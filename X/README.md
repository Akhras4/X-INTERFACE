<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="x.css" >
    <title>X</title>
</head>
<body>
  <div class="con-main">  
    <div class="con-left">
            <img src="x.avif" width="80%" height="80%">
    </div>
    <div class="con-right">
        <div class="con-signup">
            <h2>Happening now</h2>
            <h3>Join today.</h3>
            <a class="but-acc" href="#"><img src="2993685_brand_brands_google_logo_logos_icon.png" width="30px" height="30px" style="padding-right: 10px;">Sign up with Apple</a>
            <a class="but-acc" href="#"><img src="104490_apple_icon.png" width="30px" height="30px" style="padding-right: 10px;">Sign up with Apple</a>
            <div class="line">
                <div class="line-bo"></div><p class="ps">or</p><div class="line-bo"></div>
            </div>
            <a class="but-acc" id="but-acc" href="#" onclick="dialog_show()">Create account</a>
            <p>By signing up, you agree to the <a id="link-t" href="#">Terms of Service</a> and <a href="" id="link-t">Privacy Policy</a>, including<a href="" id="link-t"> Cookie Use.</a></p>
            <h3>Already have an account?</h3>    
            <a class="but-acc" id="but-acc1" href="#">Sign in</a>
        </div>
    </div>
  </div>
  <dialog id="dialog-co">
    <form>
        <div id="dialog-bor" style="display: block;">
            <div id="dialog-step">
                <button class="close" onclick="dialog_close()">close</button>
                <div class="dialog-f"> 
                <h4>Step 1 of 2</h4>
                <h1>Create your account</h1>
            
                    <div class="name" >
                        <label>Name</label>
                        <input type="text" required min="1" max="50">
                    </div>
                    <div class="name" >
                        <label>Email</label>
                        <input type="email" required >
                    </div>    
                        <label for="">Date of birth </label>
                        <p>This will not be shown publicly. Confirm your own age, even if this account is for a business, a pet, or something else.</p>
                    <div class="name" >
                        <label for="">Date of birth </label>
                        <input type="date">
                    </div>
                    <a class="dialog-next" id="dialog-next" href="#" onclick="dialog_step2()">Next</a>
                </div>
             </div>
        </div>
        <div id="dialog-bor1" style="display: none;">
            <div id="dialog-step1" >
                <button class="but-back" onclick="dialog_step1_back()">back</button>
                <div class="dialog-f2">
                    <h4>Step 2 of 2</h4>
                    <h3>Get more out of X</h3>
                    <div class="con-che">
                         <label for="">Receive email about your X activity and recommendations.</label>
                         <input  type="checkbox">
                    </div>
                    <h3>Connect with people you know</h3>
                    <div class="con-che">
                        <label for="">Let others find your X account by your email address.</label>
                        <input type="checkbox"  >
                    </div>
                    <h3>Personalized ads</h3>
                    <div class="con-che">
                        <label for="">You will always see ads on X based on your X activity. When this setting is enabled, X may further personalize ads from X advertisers, on and off X, by combining your X activity with other online activity and information from our partners.</label>
                        <input type="checkbox">
                    </div>
                    <p>By signing up, you agree to our Terms, Privacy Policy, and Cookie Use. X may use your contact information, including your email address and phone number for purposes outlined in our Privacy Policy. Learn more</p>
                    <a class="dialog-next" id="dialog-next" href="#" onclick="dialog_step2()">Next</a>
                </div>
             </div>
        </div>
</form>
  </dialog>
  <div class="footer">
    <a href="">About</a>
    <a href="">Download the X app</a>
    <a href="">Help Center</a>
    <a href="">Terms of Service</a>
    <a href="">Privacy Policy</a>
    <a href="">Cookie Policy</a>
    <a href="">Accessibility</a>
    <a href="">Ads info</a>
    <a href="">Blog</a>
    <a href="">Status</a>
    <a href="">Careers</a>
    <a href="">Brand Resources</a>
    <a href="">Advertising</a>
    <a href="">Marketing</a>
    <a href="">X for Business</a>
    <a href="">Developers</a>
    <a href="">Directory</a>
    <a href="">Settings</a>
    <a href="">© 2024 X Corp.</a>
  </div>
</body>
<script>
    function dialog_show(){
        var n= document.getElementById("dialog-co");
        n.showModal()
    }
    function dialog_close(){
        var n= document.getElementById("dialog-co");
        n.close()
    }
    function dialog_step2(){
        var n=document.getElementById('dialog-bor');
        var m=document.getElementById('dialog-bor1');
        n.style.display='none'
        m.style.display='block'
    }
    function dialog_step1_back(){
        var n=document.getElementById('dialog-bor');
        var m=document.getElementById('dialog-bor1');
        n.style.display='block'
        m.style.display='none'
    }
   
</script>
</html>
