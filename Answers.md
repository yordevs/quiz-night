<img src="https://user-images.githubusercontent.com/68516952/223836189-4e899747-2f5e-4632-a33a-102f4641e1b6.png" title="Yordevs Duck" width="350">

# Yordevs Quiz Night 2023  

We bid you welcome to the final Yordevs event of the term, where you'll put your web development and programming skills to the test for a chance to win a voucher!

As a quiz participant you will get free pizza! Please fill out the Google Form [here](https://quiz.yordevs.com), if you haven't already.
The Yordevs AGM will also follow this event! You can nominate yourself beforehand [here](https://nominations.yordevs.com).  

You can work individually or in a group. Choose one of the four answers for every question. You have three quarters of an hour to answer them all. Email your answers to yordevs@yusu.org by 6:35pm on 10/03/2023 to qualify for the prizes! Answers will be revealed at 6:40pm. Prizes will be awarded via email to a member of every winning team following the event, and it will be their responsibility to split the prize amongst their team.  

If you're _really_ stuck, check the footnotes[^!] for a quick nudge or ask us for help. Good luck!

[^!]: **Hint:** you may find searching [Google](https://google.co.uk), inspecting [the Yordevs website](https://yordevs.com) and [the Yordevs Links page](https://links.yordevs.com/), scouring [Yordevs GitHub](https://github.com/yordevs) or utilising [CodePen](https://codepen.io) useful for some of these questions.  

## Questions  

1. Which is a valid HTML tag?

   - `<h0>`
   - `<h10>`
   + `<h6>`
   - `<heading>`

1. This is the modal window on the Yordle website. Which of the following HTML elements is this modal window nested in?[^ß]
   
   <img src="https://user-images.githubusercontent.com/68516952/224185710-64c3696d-5e91-4761-b261-48abf4722022.png" title="Yordle Modal Popup" width="350">

   - `<header>`
   + `<body>`
   - `<footer>`
   - `<iframe>`

   [^ß]: **Guidance:**: Open your browser developer tools (Ctrl-Shift-i) and select the Elements tab to inspect the Yordle landing page's HTML. Click the element selector button (Ctrl-Shift-c), select the modal window then investigate where the modal window is located in the HTML by expanding and collapsing the HTML elements in the DOM.

1. What is the correct HTML tag for inserting a line break element?

   + `<br>`
   - `<break>`
   - `<lb>`
   - `\n`

1. Which one of the following statements relating to stylings is untrue?[^a]

   - The correct HTML for referring to an external style sheet is:
     ```HTML
     <link rel="stylesheet" type="text/css" href="styles.css">
     ```
   + You cannot refer to an external style sheet in the <head> section of a HTML document.
   - The style HTML attribute is used to define inline styles.
   - The style HTML element is used to define internal styles.

   [^a]: **Guidance:** You should refer to an external style sheet in the <head> section of a HTML document.

1. Why does the logo on the YUSU website blur when you zoom in a bit too much?[^b]
   
   <img src="https://user-images.githubusercontent.com/68516952/224081684-bd8990ce-56b8-4f08-a006-fb61fe3454d6.png" title="YUSU Logo" width="350">

   - The width and height properties were set too high in the `<img>`.
   - The logo is in an XML-based vector graphic of an SVG format.
   + The logo is in a PNG image format.
   - The `style="max-width: 200px"` shouldn't make that possible!

   [^b]: **Guidance:** SVG images do not blur when a user zooms in. `style="max-width: 200px"` is overriden if a user zooms in.

1. Using a screenreader for accessibility testing (e.g [Pericles](https://chrome.google.com/webstore/detail/pericles-text-to-speech-s/oacindbdmlbdeidohafnfocfckkhjlbg)), upon which icon in the Yordevs Website's footer does the screenreader stop working properly?

   <img src="https://user-images.githubusercontent.com/68516952/224089167-b4403383-702f-4cad-b836-d7f8d673ee58.png" title="Yordevs Footer" width="350">

   - Twitter
   - GitHub
   - Discord
   + Instagram

1. Why does the LinkedIn icon come up as an `Unknown Social Media Icon` when styling is stripped from the Yordevs website?[^c]

   <img src="https://user-images.githubusercontent.com/68516952/224126229-21afdd69-788f-4178-8e7c-c37c7173b640.png" title="Yordevs Footer Unstylinged" width="350">

   - `iconName="Link to Yordevs LinkedIn"` isn't present
   + `iconName="Link to Yordevs LinkedIn"` is misplaced
   - `icon={<FaLinkedin/>}` isn't present
   - `icon={<FaLinkedin/>}` is misplaced

   [^c]: **Guidance:** Look in [Footer.js](https://github.com/yordevs/yordevs.github.io/blob/gatsby/src/components/Footer.js) of the Yordevs website repo.

1. The following ASCII art is accompanied by which Yordevs welcome in Dev Tools on the Yordevs Website?[^d]

   <img src="https://user-images.githubusercontent.com/68516952/224125507-bfc8676b-558b-4cac-8a46-c0d8f3b703fa.png" title="ASCII Longboi Welcome" width="350">
   
   - "Hi from Longboi, and the Yordevs team!"
   - "Hello from the Yordevs team, and Longboi!"
   - "Hi from the Yordevs team, and Longboi!"
   + "Hello from Longboi, and the Yordevs team!"

   [^d]: **Guidance:** Open your browser developer tools on the Yordevs website and see the console log.

1. WCAG (Web Content Accessibility Guidelines) are guidelines published by the Web Accessibility Initiative of the World Wide Web Consortium, the main international standards organization for the Internet. Which of the following is the correct WCAG 2.0 guideline on contrast ratios?[^e]

   + WCAG 2.0 Level AA requires text or images of text to have a contrast ratio of at least 4.5:1 (or 3:1 for large text).
   - WCAG 2.0 Level A requires text or images of text to have a contrast ratio of at least 7:1 (or 4.5:1 for large text).
   - WCAG 2.0 Level AAA requires text or images of text to have a contrast ratio of at least 4.5:1 (or 3:1 for large text).
   - WCAG 2.0 Level AAAA requires text or images of text to have a contrast ratio of at least 7:1 (or 4.5:1 for large text).

   [^e]: **Guidance:** WCAG at Level A sets a bare minimum level of accessibility. Level AA or AAA conformance is best for all web based content. WCAG 2.0 Level AAA requires text or images of text to have a contrast ratio of at least 7:1 (or 4.5:1 for large text). AAAA does not exist as a level for WCAG.

1. Using an accessibility testing tool (e.g [WAVE](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)), you can check if any contrast errors are present on a website. Thankfully, there are none on the Yordevs Website - but there is one error. Which of the following WCAG guidelines, is this error not compliant with?[^f]

   <img src="https://user-images.githubusercontent.com/68516952/224108335-afccb587-1563-4fa0-be4a-76e687e4d949.png" title="Yordevs WAVE Test" width="350">  
   <img src="https://user-images.githubusercontent.com/68516952/224112554-93600b69-2100-404c-9703-5f7234a4f685.png" title="Yordevs WAVE Error" width="350">

   - [4.1.2 Name, Role, Value (Level A)](https://webaim.org/standards/wcag/checklist#sc4.1.2) 
   - [1.1.1 Non-text Content (Level A)](https://webaim.org/standards/wcag/checklist#sc1.1.1) 
   + [3.1.1 Language of Page (Level A)](https://webaim.org/standards/wcag/checklist#sc3.1.1)
   - [2.4.4 Link Purpose (In Context) (Level A)](https://webaim.org/standards/wcag/checklist#sc2.4.4)

   [^f]: **Guidance:** It's mentioned in the Yordevs WAVE Error image.
   
1. Which of these hex codes is part of the Yordevs branding?[^g]
   
   + #AA211A
   - #2B434C
   - #DED45B
   - #9D140D

   [^g]: **Guidance:** Inspect the Yordevs website's styling and convert the RGB code to Hex code. Alternatively search the [Yordevs website repo](https://github.com/yordevs/yordevs.github.io). The incorrect answers were Yordevs colours dimmed/lightened by marginal percentages, so that eyeballing it via the logo wouldn't work as well...

1. Which event occurs when a user clicks on an HTML element?

   + onclick
   - onmouseover
   - onmouseclick
   - onchange

1. Meet the Yordevs duck's distant cousin. In the following HTML code block containing internal CSS, what hex code represents the colour of the body class?[^h]

   ```HTML
   <!DOCTYPE html>
   <html>
      <head>
         <style>
            body {
              padding: 0;
              margin: 0;
              background: #FFFFFF;
            }
            .circle {
              position: relative;
              display: block;
              width: 500px;
              height: 500px;
              background: #284049;
              margin: 0 auto;
              border-radius: 50%;
            }
            .beak {
              position: absolute;
              border-top: 100px solid #E85454;
              border-right: 50px solid transparent;
              border-left: 25px solid transparent;
              margin-left: 30px;
              margin-top: 150px;
              transform: rotate(90deg);
            }
            .head {
              position: absolute;
              left: 75px;
              top: 80px;
              background: #F7ED74;
              border-radius: 50%;
              width: 180px;
              height: 180px;
            }
            .body {
              position: absolute;
              left: 75px;
              top: 240px;
              background-color: #F7ED74;
              width: 400px;
              height: 230px;
              border-radius: 30% 70% 50% 30% / 50% 0 100% 50%;
            }
            .wing {
              display: none;
            }
            .red-wing {
              position: absolute;
              border-top: 140px solid #9D140D;
              border-right: 80px solid transparent;
              border-left: 80px solid transparent;
              transform: rotate(150deg);
              margin-left: 150px;
              margin-top: 270px;
            }
            .yellow-wing {
              position: absolute;
              border-top: 140px solid #F7ED74;
              border-right: 80px solid transparent;
              border-left: 80px solid transparent;
              transform: scale(0.75) rotate(150deg);
              margin-left: 140px;
              margin-top: 275px;
            }
            .cursor {
              position: absolute;
              border-top: 30px solid #9D140D;
              border-right: 15px solid transparent;
              border-left: 10px solid transparent;
              transform: rotate(155deg);
              margin-left: 110px;
              margin-top: 130px;
            }
            .cursor-tail {
              position: absolute;
              background-color: #9D140D;
              height: 10px;
              width: 10px;
              transform: rotate(65deg);
              margin-left: 125px;
              margin-top: 155px;
            }
         </style>
      </head>
      <body>
         <div class="circle">
           <div class="duck">
             <div class="body"></div>
             <div class="beak"></div>
             <div class="head"></div>
             <div class="eye">
               <div class="cursor"></div>
               <div class="cursor-tail"></div>
             </div>
             <div class="wing">
               <div class="red-wing"></div>
               <div class="yellow-wing"></div>
             </div>
           </div>
         </div>
      </body>
   </html>
   ```

   - #E85454
   - #284049
   + #F7ED74
   - #FFFFFF

   [^h]: **Guidance:** The element(s) of class body is coloured #F7ED74, whereas the body HTML element is coloured #FFFFFF.

1. Using the same HTML code as the previous question, you may have noticed that our distant cousin is wingless. Which is the smallest _change in the code_ that wings the poor duck?[^i]

   - Remove `display: none;` from the `wing` class styling
   + Replace `wing` by `wings` in the internal CSS
   - Replace `red-wing` by `red-wings` in the HTML document body
   - Add `display: block !important;` to both `red-wing` and `yellow-wing` class stylings

   [^i]: **Guidance:** Smallest change, not the change that results in the shortest code. Replacing `wing` by `wings` causes the `display: none;` property to no longer be inherited by `red-wing` and `yellow-wing`.  

1. Going up the Yordevs family tree for a quick history lesson. Who of the following is the oldest of the long lost Yordevs ancestors?[^2][^j]
   
   - <img src="https://user-images.githubusercontent.com/68516952/223913883-74d9cec4-6452-4db5-a092-941ee906cdf2.png" title="Yordevs Ancient Logo 1" width="350">
   + <img src="https://user-images.githubusercontent.com/68516952/223913881-25d96dc9-d305-400a-9609-bbb02e4bdbce.png" title="Yordevs Ancient Logo 2" width="350">
   - <img src="https://user-images.githubusercontent.com/68516952/223914406-3e7dcd31-9244-4911-8681-10e510aa7b66.png" title="Yordevs Ancient Logo 3" width="350">
   - <img src="https://user-images.githubusercontent.com/68516952/223913884-b44ea022-e5a2-4d47-b391-7494d3e51781.png" title="Yordevs Ancient Logo 4" width="350">

   [^2]: **Hint:** They were crafted using _only_ CSS!  

   [^j]: **Guidance:** [If you go back far enough in the Yordevs website GitHub commit history...](https://github.com/yordevs/yordevs.github.io/commit/fbd26555f472469999a12b6666b48a37ee1558f2#diff-c3304bc069fb052ecac4e65e4b66572896e67e3612fa0e22d98bb9248c04151d)

1. Which of these statements concerning the HTML alt attribute is false?[^k]
   
   - Null alt attributes should only be used for decorative images.
   - Alt attributes specify alternative information about an image, which is used if a user cannot view it (e.g. due to a slow connection, an error in the src attribute, or if a screen reader is used).
   - The alt attribute is required if the href attribute is present.
   + The HTML:
     ```HTML
     <img src="" alt="The Yordevs Duck">yordevs-duck.png</img>
     ```
     adds a PNG image named yordevs-duck.png with alternative text 'The Yordevs Duck' to a page.

   [^k]: **Guidance:** The HTML:
         ```HTML
         <img src="yordevs-duck.png" alt="The Yordevs Duck">
         ```
         adds a PNG image named yordevs-duck.png with alternative text 'The Yordevs Duck' to a page.

1. Which HTML tag formats elements as a numbered list?

   + `<ol>`
   - `<list>`
   - `<dl>`
   - `<ul>`

1. Which is the correct HTML hyperlink?

   - ```HTML
     <a url="http://www.yordevs.com">Yordevs</a> <!-- This one is -->
     ```
   - ```HTML
     <a name="http://www.yordevs.com">Yordevs</a> <!-- No, that one is -->
     ```
   - ```HTML
     <a>http://www.yordevs.com</a> <!-- Yes, this one is! -->
     ```
   + ```HTML
     <a href="http://www.yordevs.com">Yordevs</a> <!-- No, this is -->
     ```

1. What message is displayed on the Yordevs Links page if the source is specified as a QR code?[^3][^l]  

   + "If you can scan a qr code you can make a website, why not use these links to find out more about us"
   - "You've come from a qr code? Why not join us and find out how we knew!"
   - "You clicked our link on a qr code? I didn't even know you could do that!"
   - "This link was shared via a qr code? Good job I wrote the code for this message then!"

   [^3]: **Hint:** Check out URL query strings and parameters!

   [^l]: **Guidance:** Navigate to https://links.yordevs.com/?source=qr. Alternatively search the [Yordevs Links page repo](https://github.com/yordevs/links.yordevs.com) to get to [App.js](https://github.com/yordevs/links.yordevs.com/blob/master/src/App.js).

1. What backend does this Contact Us form on the Yordevs Website use?[^m]  
   
   <img src="https://user-images.githubusercontent.com/68516952/223878998-f14bb974-159b-4ced-9fcd-233d3c774751.png" title="Yordevs Contact Us" width="350">
   
   - Formbold
   - Formcake
   + Formspree
   - Formspark

   [^m]: **Guidance:** They are all valid form backend services! Inspect the Contact Us form's HTML in your browser developer tools.  

1. The HTML code for the textarea of the Contact Us form in the previous question is as follows:

   ```HTML
   <textarea cols="30" rows="5" placeholder="Your message here..." name="textarea" id="message"
             class="ContactForm__FormInput" style="resize: vertical; max-width: 100%;">
   </textarea>
   ```
   
   Is this textarea an accessible HTML element?
   
   - Yes, as `placeholder` and `name` are specified.
   - Yes, as `name` and `class` are specified.
   - No, as `tab-index` and `label` are not specified.
   + No, as `label` and `aria-label` are not specified.
   
1. Which HTML is valid for a hyperlink that opens a link in a new browser window upon click?

   - ```HTML
     <a href="url" new>
     ```
   + ```HTML
     <a href="url" target="_blank">
     ```
   - ```HTML
     <a href="url" target="new">
     ```
   - ```HTML
     <a href="url" target="blank">
     ```

1. Where on the whole wide web can you find this homage to Yordevs?[^n]

   <img src="https://user-images.githubusercontent.com/68516952/224188232-71904736-4ec3-4925-952c-03e6f14b3fd1.png" title="Yordevs Shoutout" width="350">  

   + The Lemon Press website
   - The Longboi Locator website
   - The Ebor Lex Journal website
   - The Yordle website

   [^n]: **Guidance:** The font style may have been telling, but if you refresh the Lemon Press website often enough you'll see the footer changes.  

1. How many ducks are present on the Yordevs Links page?[^o]  

   + 170
   - 180
   - 200
   - 150

   [^o]: **Guidance:** Search the [Yordevs Links page repo](https://github.com/yordevs/links.yordevs.com) to get to [Background.js](https://github.com/yordevs/links.yordevs.com/blob/master/src/Background.js). An object with key "number" contains a dictionary as value, in which `"value": 170`.  

1. Which of the following statements about the `<script>` HTML element is false?[^p]

   + External JavaScript files must contain the `<script>` tag.
   - JavaScript, enclosed by `<script>` tags, can be present in both the `<head>` and `<body>` sections of a HTML document.
   - `<script src="index.js">` is the correct syntax for referring to an external script in a file called `index.js`.
   - JavaScript is put in the `<script>` HTML element.

   [^p]: **Guidance:** A HTML element would not be present in a JavaScript file. For clarity, it's best practice to have external or internal JavaScript in the head of a HTML file, but it should be noted that the JS code runs before the remaining DOM content loads from the HTML code (to adjust, see [this Stack Overflow answer](https://stackoverflow.com/a/24070373)).
        
1. What HTTP request method gets you rick rolled on the Yordle Server?[^q]:   

   - DELETE
   - POST
   - PUT
   + GET

   [^q]: **Guidance:** Fetching data (a GET request) when navigating to https://api.yordle.co.uk/ redirects you. Alternatively, in [index.ts](https://github.com/yordevs/yordle-server/blob/master/index.ts) of the [Yordle Server repo](https://github.com/yordevs/yordle-server), you can see:
         ```TypeScript
         app.get("*", (req, res) => {
          res.redirect("https://www.youtube.com/watch?v=dQw4w9WgXcQ")
         })
         ```
        
1. What HTTP status code (although _slightly_ misleadingly) is accompanied by [this response](https://raw.githubusercontent.com/yordevs/yordle-server/master/resources/forbiddenResponse.txt) on the Yordle Server upon an POST request with an invalid body?[^r]  

   + 403
   - 200
   - 400
   - 402

   [^r]: **Guidance:** A forbidden response is usually accompanied by a 400 HTTP status code (not 403, as it currently does for the Yordle website), hence the '_slightly_ misleadingly'. The forbidden response is received along with a 403 status code if the body of a POST request is invalid. Alternatively, search the [Yordle Server repo](https://github.com/yordevs/yordle-server) for `forbiddenResponse` (`forbiddenResponse.txt` yields no response) to get to [index.ts](https://github.com/yordevs/yordle-server/blob/8229d1b2620ffbc57e3b961a8ee5af4536091f2b/index.ts) and find the following code blocks:
         ```TypeScript
         var forbiddenResponse: string;
         fs.readFile('resources/forbiddenResponse.txt', 'utf8', function (err, data) {
          if (err) throw err;
          forbiddenResponse = data;
         });
         ```
         ```TypeScript
             } else {
              res.status(403).send(forbiddenResponse);
             };
         ```

1. Which is the correct HTML tag to enclose important text

   - `<important>`
   + `<strong>`
   - `<b>`
   - `<i>`

1. Which of these would enable you to select all p elements inside div elements in CSS?

   - `div + p`
   - `p -> div`
   + `div p`
   - `div.p`  

1. What is the purpose of meta tags?

   - To only store information about browsers.
   + To store data relevant to web browsers and search engines.
   - To only store information about search engines.
   - To only store information about users.   
   
1. Which of the following HTMLs ensures that a valid and untruncated meta description will be displayed in Google search results?[^s]

   + ```HTML
     <head>
         <meta name="description" content="This is an example of a
     meta description. This will often show up in search results.">
     </head>
     ```
   - ```HTML
     <body>
         <meta name="description" content="This is another example of a
     meta description. This may or may not show up in search results.">
     </body>
     ```
   - ```HTML
     <body>
         <meta name="description" content="This is yet another example of a
     meta description. Meta descriptions should be under 160 characters as 
     any characters over may be truncated by search engines like Google 
     (pre-2018).">
     </body>
     ```
   - ```HTML
     <head>
         <meta name="description" content="This is but another example of a
     meta description. Neither meta descriptions nor meta keywords factor 
     into Google's ranking algorithms for web search, so count yourself
     lucky if you will.">
     </head>
     ```

   [^s]: **Guidance:** Although meta title and meta descriptions can be of any length, when displayed as website snippets on search engine results pages, they are truncated typically to fit the device width. Google truncates meta titles to under 60 characters and meta descriptions to under 160 characters, but this can vary.
        
1. Why is the SERP (Search Engine Results Page) snippet different from the meta description declared in the HTML for the Yordevs NextJS Tutorial? 

   <img src="https://user-images.githubusercontent.com/68516952/224222615-05ea8d64-948f-45dc-9bb0-5b7be02251eb.png" title="SERP snippet" width="350">  

   ```HTML
   <meta data-react-helmet="true" name="description" content="The official website for Yordevs, the University 
                                                              of York's Web Development society!">
   ```
        
   - Search engines overrule meta descriptions of pages when they detect a lot of relevance between the existing meta description of a result page and a user search query. Instead they use other snippets from the page that may be less relevant.
   + Search engines overrule meta descriptions of pages when they detect little relevance between the existing meta description of a result page and a user search query. Instead they use other snippets from the page that may be more relevant.
   - Search engines change the meta descriptions of pages when they detect little relevance between the existing meta description of a result page and a user search query. Instead they use other snippets from the page that may be more relevant.
   - Search engines change the meta descriptions of pages when they detect a lot of relevance between the existing meta description of a result page and a user search query. Instead they use other snippets from the page that may be more relevant.  

1. SEO (Search Engine Optimisation) work aims to improve website traffic to a website via search engines by improving the page rank (position in search rankings). Which of the following statements about SEO is false?[^t]

   - Offpage SEO measures are applied outside of a website. Tactics include link building, guest posting and social media marketing. Offpage SEO aims to build your website's reputation and credibility.
   - Onpage SEO tactics are applied directly within a website. Examples include measures to optimise the content or improve the meta description and title tags.
   + White hat SEO strategies exclude link building, quality content creation, improving website performance, using descriptive meta tags, improving site navigation and utilising responsive web design.
   - Black hat SEO techniques are unethical (but not illegal) SEO practices that clash with search engine guidelines and often result in penalties from search engines. Examples include keyword stuffing, cloaking, blog commenting, user-generated content spamming, using private link networks and even hacking.

   [^t]: **Guidance:** White hat SEO strategies include link building, quality content creation, improving website performance, using descriptive meta tags, improving site navigation and utilising responsive web design.  

1. What HTML form input presents multiple options, but allows the selection of only one?

   - `<input type="text">`
   + `<input type="radio">`
   - `<input type="checkbox">`
   - `<textarea>`

1. What is the correct JavaScript code to change the content of the HTML element below?[^u]

   ```HTML
   <p id="hello">Hello World!</p>
   ```

   - ```JavaScript
     #hello.innerHTML = "Hello Yordevs!";
     ```
   - ```JavaScript
     document.getElementByName("p").innerHTML = "Hello Yordevs!";
     ```
   + ```JavaScript
     document.getElementById("hello").innerHTML = "Hello Yordevs!";
     ```
   - ```JavaScript
     document.getElement("p").innerHTML = "Hello Yordevs!";
     ```

   [^u]: **Guidance:** Use [CodePen.io](https://codepen.io/) to test the changes.

1. Which of these is a valid HTML code snippet?[^v]

    - ```HTML
      <h1> Yordevs Quiz Night 2023
      <h2> Questions
      ```
    - ```HTML
      </h1> Yordevs Quiz Night 2023<h1>
      </h2> Questions<h1>
      ```
    + ```HTML
      <h1>Yordevs Quiz Night 2023</h1>
      <h2>Questions</h2>
      ```
    - ```HTML
      <h1>Yordevs Quiz Night 2023<h1>
      <h2>Questions<h2>
      ```

   [^v]: **Guidance:** Check in a HTML validator (e.g. [this one](https://validator.w3.org/#validate_by_input), although note that it validates HTML documents (not just code snippets), so expects the doctype declaration and other elements too).
      
1. What is the correct HTML for making a checkbox?

   - `<check>`
   - `<checkbox>`
   - `<input type="check">`
   + `<input type="checkbox">`

1. This is the Yordevs website's nav bar. What HTML tag should enclose the elements of the nav bar?  
   
   <img src="https://user-images.githubusercontent.com/68516952/224137068-d8fd525d-9484-4d24-b125-db44894da117.png" title="Yordevs Nav Bar" width="350">  

   - `<navbar>`
   - `<section>`
   - None, as they are enclosed by `<header>`
   + `<nav>`

1. When you hover over an item on the Yordevs nav bar, the change is very visual. Which of the following is not a valid reason, according to the WCAG 2.0 guidelines, for this?[^w]

   <img src="https://user-images.githubusercontent.com/68516952/224136816-5166bd30-07d8-4682-b962-b77d03828aaa.png" title="Yordevs Nav Bar on Hover" width="350">
   
   - A change in text decoration (usually an underline) upon mouse hover and keyboard focus is sufficient enough to indicate a hyperlink, as users are accustomed to seeing links underlined.
   + A change in colour upon mouse hover and keyboard focus is sufficient enough to indicate a hyperlink, even if some users have low vision, color deficiency, or page color overrides.
   - Links should look like links, and nothing else should.
   - Alternative visual mouse hover effects (such as background glows, drop shadows, color changes) for navigation links can help users know that an element is clickable.

   [^w]: **Guidance:** A change in colour upon mouse hover and keyboard focus is not sufficient enough to indicate a hyperlink, as some users have low vision, color deficiency, or page color overrides.

1. Keyboard users utilise the tab and shift-tab keys to navigate through interactive web page elements. Visual indication of the element with current keyboard focus, called a focus indicator, is thus useful for sighted keyboard users. An example of a focus indicator on the button link to the Yordevs Website from the Yordevs Links page is shown. To ensure the same visual presentation is available upon both mouse hover or keyboard focus, any time `a:hover` is adjusted in CSS, `a:focus` should be too. Which of the following elements on the Yordevs website does not provide focus indication?

   <img src="https://user-images.githubusercontent.com/68516952/224175831-19a09136-62c8-48d1-8fa0-e84fac90d621.png" title="Links Focus Indicator Example" width="350">  

   - <img src="https://user-images.githubusercontent.com/68516952/224176408-a180579e-004e-4153-8277-cab3b1aeab54.png" title="Focus Indicator 1" width="350">
   + <img src="https://user-images.githubusercontent.com/68516952/224176797-474487cc-4db1-4c3b-99de-cd424ea6314d.png" title="Focus Indicator 2" width="350">
   - <img src="https://user-images.githubusercontent.com/68516952/224177236-0191861c-05f6-4d75-81ee-053bf9c2d60c.png" title="Focus Indicator 3" width="350">
   - <img src="https://user-images.githubusercontent.com/68516952/224176940-4b7e5170-3039-4f4a-85d4-2fe6348b7e57.png" title="Focus Indicator 4" width="350">

1. Which of these is the biggest setback for keyboard users when navigating the Yordevs website when zoomed in at 125%+ or on a smaller viewport?[^x]

   <img src="https://user-images.githubusercontent.com/68516952/224178311-6d3e5a75-8c9b-4ce3-aac4-15593eacf9aa.png" title="Smaller Viewport" width="350">
   
   + The burger menu is not keyboard focusable.
   - There is no focus indicator on the Yordevs logo.
   - There is no focus indicator on the `Blogs` navigation link.
   - The tab order is awesome!

   [^x]: **Guidance:** As of yet, keyboard users are unable to navigate the Yordevs website via the nav bar.

1. What are `<div>` tags used for in a HTML document?
   - To replace paragraphs (i.e. `<p>` tags).
   - To create hyperlinks.
   + To logically divide the document.
   - To create space between sections of a document.

1. Which of these is syntactically correct JavaScript for opening a new window redirecting to the Yordevs website?[^y]

   - ```JavaScript
     var yd = window.new("https://yordevs.com/");
     ```
   - ```JavaScript
     var yd = open.window("https://yordevs.com/");
     ```
   - ```JavaScript
     var yd = new.window("https://yordevs.com/");
     ```
   + ```JavaScript
     var yd = window.open("https://yordevs.com/");
     ```

   [^y]: **Guidance:** Test the codes out in a [W3Schools Tryit Editor](https://www.w3schools.com/jsref/met_win_open.asp).

1. Which HTML attribute is used to specify that an form element input field has to be filled out?

   - formvalidate
   - validate
   + required
   - placeholder

1. What is the output on the console after running the following JavaScript code containing regex?[^z]

   ```JavaScript
   const input = "Remember then to send this tonight!";

   const find = /.*(?:r\s)(.*)(?:n\s)(?:.*)(?:\ss)(.*)(?:\sth)(.*)(?:\sto)(?:([^t]*)(?:t)([^t]*))*/;
   const replace = "$1 $2 $3 $4$5";

   console.log(input.replace(find, replace));
   ```

   - to end this night!
   + the end is nigh!
   - send this then!
   - hen night to remember!

   [^z]: **Guidance:** Run the code in the JavaScript console in your browser developer tool (Ctrl-Shift-i). You can also test out regexes in an online regular expression tester e.g. [regex101](https://regex101.com/).

## Conclusion
Aaaand you're done - phew! Congratulations on getting here. Just remember to send your answers in an email off to yordevs@yusu.org!

## Answers

C  B  A  B  C  D  B  D  A  C  A  A  C  B  B  D  A  D  A  C  D  B  A  A  A  D  A  B  C  B  A  B  B  B  C  C  D  D  B  B  A  C  D  C  B  
