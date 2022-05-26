# run-buddy
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title> Run Buddy</title>
        <link rel="stylesheet" href="./assets/css/style.css" />
    </head>
    <body>
        <header>
            <h1 style="color: blue; font-size: 36px;">
                <a href="/">RUN BUDDY</a>
            </h1>
            <nav>
                <!-- Unordered list element-->
                <ul>
                    <!-- List item element-->
                    <li>
                        <!-- Anchor element-->
                        <a href="#what-we-do">What We Do</a>
                    </li>
                    <li>
                        <a href="#what-you-do">What You Do</a>
                    </li>
                    <li>
                        <a href="#your-trainers">Your Trainers</a>
                    </li>
                    <li>
                        <a href="#reach-out">Reach Out</a>
                    </li>
                </ul>
            </nav>
        </header>
        <!--hero section-->
        <section class="hero">
            <div class="hero-form">
                <h3>Get Started Today!</h3>
                <p>Fill out this form and one of our trainers will schedule a consult</p>
                <form>
                    <label for="name">Enter full name:</label>
                    <input class="form-input" type="text" placeholder="Your Name" name="name" id="name" />                            
                    <label for="email">Enter email address:</label>
                    <input class="form-input" type="email" placeholder="Email Address" name="email" id="email" />
                    <label for="phone">Enter a telephone number:</label>
                    <input class="form-input" type="tel" placeholder="Phone Number" name="phone" id="phone" />  
                    <p>
                         Have you worked out with a trainer before?
                        <input type="radio" name="trainer-confirm" id="trainer-yes" />
                        <label for="trainer-yes">Yes</label>
                        <input type="radio" name="trainer-confirm" id="trainer-no" />
                        <label for="trainer-no">No</label>
                    </p>
                    <p>
                        <label for="checkbox" >
                        I acknowledge that I am at least 18 years of age
                        </label>
                        <input type="checkbox" name="age-confirm" id="checkbox"/>
                        </p>
                        <button type="submit">
                            Get Running!
                        </button>
                    </form>
            </div>
        </section>
        <!--end hero-->
       <!--hero/jumbotron -->
        <section>
        </section>
        <!--"what we do" section-->
        <section id="what-we-do" class="intro">
            <h2 class="section-title primary-border">What we do</h2>
            <p>
                Butcher selfies chambray chic gentrify readymade us Echo Park XOXO Tumblr normcore Banksy direct trade Blue Bottle chillwave you probably haven't heard of them single-origin coffee Vice fanny pack fixie Odd Future Austin fingerstache pickled twee synth Wes Anderson Thundercats viral bitters flannel meggings narwhal Marfa Schlitz sustainable Intelligentsia umami deep v craft
            </p>
        </section>
        <!--"what you do" section-->
        <section id="what-you-do" class="steps">
            <h2 class="section-title secondary-border">What You Do</h2><div>
                <h3>Step 1: <span>Fill Out the Form Above.</span></h3>
                <p>You're already here, so why not?</p>
            </div>
<div>
<h3>Step 2: <span>Consult with One of Our Trainers.</span></h3>
                <p>Are you here to build muscle, lose weight, or just feel good?</p>
            </div>
 <div>
                <h3>Step 3: <span>Get Running.</span></h3>
                <p>Hit the ground running (literally) once your trainer lays out your plan.</p>
            </div>
 <div>
                <h3>Step 4: <span>See Results.</span></h3>
                <p>Bi-weekly checkins with your trainer will keep you focused</p>
            </div>
        </section>
      <!--"meet the trainers" section-->
        <section id="your-trainers" class="trainers">
            <h2 class="section-title primary-border">Meet The Trainers</h2>
            <article class="trainer">
                <div class="trainer-bio text-left">
                    <h3> Arron Sthephens</h3>
                    <h4>Speed / Strength</h4>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis atque corrupti ut mollitia fuga rerum totam quo nulla at amet, illo temporibus laudantium quia voluptatibus molestias aliquam, harum possimus ipsam?
                    </p>
                </div>
            </article>
            <article class="trainer">
                <div class="trainer-bio text-right">
                    <h3>Joanna Gill</h3>
                    <h4>Endurance</h4>
                    <p>
                        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Accusamus quidem repudiandae magni saepe deleniti non. Quas modi nisi est ea optio tempora cumque error id! Consectetur illo inventore quis et?
                    </p>
                </div>    
            </article>
            <article class="trainer">
                <div class="trainer-bio text-left">
                    <h3>Harry "the Headband" Smith</h3>
                    <h4>Strength</h4>
                    <p>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis, ab quaerat. Qui expedita nemo quisquam debitis modi mollitia nostrum repellat nesciunt vitae, amet voluptatem ipsa placeat quia quae non quas!
</p>
                </div>
            </article>
        </section>
<!--"reach out" section-->
        <section id="reach-out" class="contact">
            <h2 class="section-title secondary-border">Reach Out</h2>
            <div class="contact-info">
            <div>
                <h3>Run Buddy</h3>
                <p>
                    Any questions or concerns before signing up?
                    <br/>
                    Let us know and we'll be happy to talk to you!
                </p>
                <address>
                    55 Main Street<br/>
                    Some Town, CA <br/>
                    12345<br/>
                    P: 555.RUN.BUDZ (555.786.2839)<br/>
                    E: <a href="mailto:info@runbuddy.io">infor@runbuddy.io</a>
                </address>
            </div>
        </section>
        <!--footer-->
        <footer>
            <h2>❤️ Made with love by Run Buddy.</h2>
            <div>
                <a href="./privacy-policy.html">Read Our Privacy Policy</a><br />
                &copy; 2019 Run Buddy, Inc.
            </div>
        </footer>
    </body>
</html>
