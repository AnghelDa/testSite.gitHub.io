<!DOCTYPE html>
<html lang="en-US">

    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width" />
        <title>Sport and mental health</title>
        <link rel="stylesheet" href="styles/my-css-file.css">
        <link rel="icon" href="favicon.ico" type="image/x-icon"/>

        <style>
            div {
                width: 30%;
                display: inline-block;
            }
        </style>
    </head>

    <body>
        <header>
            <nav>

            </nav>
        </header>

        <main>
            <article>
                <section>
                    <h2>Links</h2>

                    <a href="https://www.lesmills.com" target="_blank">[external link] Les Mills Page</a>
                    <a href="page2.html" target="_blank">[relativ link] Get member acces</a>
                    <a href="dir1/page3.html" target="_blank">Optional workout plan</a>
                    <a href="images/razboinic.jpg" target="_blank">Do not forget to strech</a>

                </section>
                <section>

                </section>
            </article>

            <img src="images/1_images.jpeg" alt="Girl work out on the beach." width="400" height="300"> </a>

            <p title="I'm a tooltip">Regular trainning maintains mental health.</p>

            <h1>Exercise routine</h1>

            <p>Adding variety to your workout routine will 
            not only prevent it from becoming dull but
            will also keep your body challenged for maximum results.</p>
        
            <pre>
                Work out a lot.

                Work out early.

                Work out often.

                Work out and have fun.

                Choose your work out plan.
            </pre>

            <p><a href="https://try.lesmillsondemand.com/yoga-30/?gad_source=1&gclid=Cj0KCQiAwP6sBhDAARIsAPfK_wZQCyEBkofcl3AZ_ZUUacDThmaR0dxQApE_ilVCR3cAfeGG-fJkEOsaAnSjEALw_wcB&gclsrc=aw.ds" 
            target="_blank">Try this one, is great!</a></p>

            <p class="center">I'm starting to learn CSS.</p>
            
            <div>
                <p>
                Going to gim 5 days a week, working all tipe of muscle, <span>involving all muscle groups</span>,
                it improves the general physical condition, 
                brings major benefits to mental health and considerably improves the quality of life, in general.
                </p>
            </div>
            
            <ul type="disc">
            <li class="special">Body Pump</li>
            <li>Ecore</li>
            <li>HIIT</li>
            </ul>

            <ol type="1">
            <li>Body Pump</li>
            <li>Ecore</li>
            <li>HIIT</li>
            <li>Body Pump</li>
            <li>Ecore</li>
            <li>Rest</li>
            <li>Rest</li>
            </ol>

            <dl>
                <dt>Body Pump</dt>
                <dd>Bar, disc and stepper training for all muscle groups.</dd>
                
                <dt>Ecore</dt>
                <dd>Training of our central area, made up of 8 main muscles. 
                    We use the elastic band, small and medium weights, the mattress.</dd>

                <dt>HIIT</dt>
                <dd>High Intensity Interval Training. 
                    We use the bar and discs in the Strength version, or just your own weight in the cardio version.</dd>
            </dl>


            <form>
                <fieldset>
                    <legend>Text input fields:</legend>

                    <label for="fname">First name:</label>
                    <input type="text" id="fname" name="fname" value="my first input">
                    
                    <label for="lname">Last name:</label>
                    <input type="text" id="lname" name="lname" value="my second input">

                    <input type="submit" value="Submit">
                </fieldset>
            </form>
            
            <h2>Radio Buttons</h2>
            
            <form>
                <fieldset>
                    <legend>Choose your favorite Web language:</legend>

                    <input type="radio" id="html" name="fav_language" value="HTML">
                    <label for="html">HTML</label>

                    <input type="radio" id="css" name="fav_language" value="CSS">
                    <label for="css">CSS</label>
                    
                    <input type="radio" id="javascript" name="fav_language" value="JavaScript">
                    <label for="javascript">JavaScript</label>
                </fieldset>
            </form>
            
            <h2>Check boxes</h2>
            <form>
                <fieldset>
                    <legend>How many time do you workout in a week?</legend>
                    
                    <input type="checkbox" id="onetime" name="onetime" value="one">
                    <label for="onetime">One Time</label>

                    <input type="checkbox" id="twotimes" name="twotimes" value="two">
                    <label for="twotimes">Two Times</label>

                    <input type="checkbox" id="threetimes" name="threetimes" value="three">
                    <label for="threetimes">Three Times</label>

                    <input type="checkbox" id="fourtimes" name="fourtimes" value="four">
                    <label for="fourtimes">Four Times</label>

                    <input type="checkbox" id="fivetimes" name="fivetimes" value="five">
                    <label for="fivetimes">Five Times</label>
                </fieldset>
            </form>

            <h2 class="special">Dropdown menu/ selected element</h2>

            <form>
                <label for="levels">Choose your fit level:</label>

                <select id="levels" name="levels">
                    <option value="1" selected>Beginner</option>
                    <option value="2">Intermediate</option>
                    <option value="3">Advanced</option>
                </select>
            </form>

            <form>
            <fieldset>
                <label for="weekdays">Choose your favorite trainning day:</label>
                <select id="weekdays" name="weekdays" size="4" multiple>
                    <option value="monday" selected>Monday</option>
                    <option value="tuesday">Tuesday</option>
                    <option value="wednesday">Wednesday</option>
                    <option value="thursday">Thursday</option>
                    <option value="friday">Friday</option>
                    <option value="saturday">Saturday</option>
                    <option value="sunday">Sunday</option>
                </select>
            </fieldset>
            </form>
        </main>

        <footer>
            <a href="danghel2603@yahoo.com" > Send Email </a><br>
            <textarea rows="10" cols="30"></textarea><br>
            <input type="date"><br>
            <input type="range"><br>
            <input type="file"><br>

        </footer>
    </body>
</html>
