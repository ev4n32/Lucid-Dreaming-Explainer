# codeLouisville - Evan Wilson

## Lucid Dreaming Explainer ##

My project is a website designed to inform people about lucid dreaming. With an easy to use and minimalistic single page interface. Users are first guided to a YouTube video that gives a basic rundown of Lucid Dreaming. As you continue through the website you are presented with three expandable buttons each with different methods one can use to practice and achieve a lucid dream. It also gives you an option at the bottom of the page to subscribe to a newsletter. 

## Features ##

1: CSS Navbar - The navigation bar changes styles depending on the size of the screen used. If on a larger screen, the navigation bar displays the links to the right side across the bar. On smaller screens, the navigation links are displayed below the title of the website. This is done using media queries and seperate IDs (#links & #links2). 

2: CSS Animation - In the 'title' class, I created a CSS animation to make the headers slide into the center of the page. I used different animation times on the two header tags to make one header slide in slower than the first one. 

3: Newsletter Form - This form when submitted first checks to see if an '@' symbol is included in the email address. If not, the alert notifies the user that the email submitted is invalid. If the email submitted has an '@' symbol, the email is displayed back to the user and confirms that they have been added to the newsletter.

4: Expandable Buttons - The buttons on the "Methods" section of the website use javascript to either display or not display their respective content depending on if the user has clicked the button for the corresponding lucid dreaming method. The same script is used for different IDs by feeding the function different values for variable 'a' in the script.
