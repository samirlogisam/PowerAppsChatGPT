# PowerAppsChatGPT
This is a Power Apps which uses a custom connector to interact with ChatGPT
In a previous article, I described how you can use OpenAI API to create a custom connector in order to interact and query Chat GPT.

If you have missed this post, please go back and have a look

https://samtech365.com/power-platform-chatgpt-custom-connector/

If you want to download the connector manifest and import it directly to your tenant/custom connector, please navigate to my public GitHub repository :

<a href="https://github.com/samirlogisam/PowerAppsChatGPT/blob/main/DemoChatGPT.swagger.json">https://github.com/samirlogisam/PowerAppsChatGPT/blob/main/DemoChatGPT.swagger.json</a>

Once, you have configured (or imported) your custom connector, next step, is to create a simple PowerApps which uses this connector:
<h1>1- The PowerApps Structure</h1>
The App is very simple, here I used a simple screen, with the following components
<h1><a href="https://samtech365.com/wp-content/uploads/2023/06/Screenshot-2023-06-27-at-01.35.41.png"><img class="aligncenter size-full wp-image-100603" src="https://samtech365.com/wp-content/uploads/2023/06/Screenshot-2023-06-27-at-01.35.41.png" alt="" width="326" height="544" /></a></h1>
The app's screen looks as follow:
<h1><a href="https://samtech365.com/wp-content/uploads/2023/06/Screenshot-2023-06-27-at-01.35.46.png"><img class="aligncenter size-full wp-image-100604" src="https://samtech365.com/wp-content/uploads/2023/06/Screenshot-2023-06-27-at-01.35.46.png" alt="" width="501" height="905" /></a></h1>
A query text box, and an answer multi lines text box. It can't be any simpler right !
<h1>2- Ask Button</h1>
The Ask button makes a call to our custom connector <strong>DemoChatGPT.</strong>

<a href="https://samtech365.com/wp-content/uploads/2023/06/Screenshot-2023-06-27-at-01.39.42.png"><img class="aligncenter size-full wp-image-100605" src="https://samtech365.com/wp-content/uploads/2023/06/Screenshot-2023-06-27-at-01.39.42.png" alt="" width="399" height="504" /></a>

Once we call the ChatGPT Api, the result is set to a global variable, which will be displayed in the result text box.

<a href="https://samtech365.com/wp-content/uploads/2023/06/Screenshot-2023-06-27-at-01.36.08.png"><img class="aligncenter size-full wp-image-100606" src="https://samtech365.com/wp-content/uploads/2023/06/Screenshot-2023-06-27-at-01.36.08.png" alt="" width="886" height="381" /></a>

&nbsp;

The overall application and connector are available from GitHub --&gt;
<h1 style="text-align: center;"><a href="https://github.com/samirlogisam/PowerAppsChatGPT/">https://github.com/samirlogisam/PowerAppsChatGPT/</a></h1>
