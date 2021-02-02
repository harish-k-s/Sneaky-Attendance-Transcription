Sneaky Attendance Transcription (Jan 2021 build)
(A desktop application (for windows) to mine & export GMeet session-attendance as XLSX)

Directions to use this application + Insights on what you can expect it to do...!

1) Firstly, make sure that you've got the following three essential things, else the application won't work and might crash midway...
(If you've downloaded this as a zipped folder, please extract its contents into a separate folder before you start using it...)
	i) Sneaky Attendance Transcription.exe
	ii) emeraldLogo.ico
	iii) chromedriver.exe (whose version should match your current G-Chrome browser's version) 
	Visit 'https://chromedriver.chromium.org/downloads', just in case you want to download a chromedriver of your choice...
2) Just a minute or two before you join a GMeet session, launch the 'Sneaky Attendance Transcription.exe' application.

3) Fill in your google account's login credentials & the targeted GMeet session's link (or the hyphen separated GMeet id)
someone@example.com
password
https://meet.google.com/aaa-aaaa-aaa
(or even this is enough) aaa-aaaa-aaa

4) An automated chrome browser window will log you into your google account, after which it will take you to the specified GMeet page...

5) Once you arrive at the joining screen, it will automatically set the video-receive-resolution to 'Audio only', to conserve your internet expenditure ;)

6) Then, it'll click on the 'Join now' button or the 'Ask to join' button (whichever is available) & it'll enter the meet with the organizer's consent...
(Don't worry, the access-permissions to your Camera & Microphone are blocked by default & so you won't be disturbed by any permission pop-ups...)

7) It'll open up the side pane to frequently scan the list of participants... Even if the side pane is accidentally closed, it'll be automatically reopened...
That's it - We're done with setting up our 'Sneaky Transcriber ;)'
Let the automated browser window run in the background as it scans the list of participants...! Now, you can either sit back & relax or...
Go ahead & use a different browser's window or any other device of your choice to participate in the GMeet session that we've now sneaked into...

[All the above-mentioned steps seem too long in writing, but they're likely to happen so rapidly, within just a minute or two...
Everything is properly chained & intended to happen as smooth as possible, so try not to interact with the automated browser window,
unless it stays longer than a minute on the same screen...]

8) When the session is about to end, before people start leaving, click on the 'red, inverted telephone' button in the automated browser window... 
As soon as you click it, the automated browser window will close itself & the observed attendance is transcribed into XLSX, named by date...
A mini thank-you-kind-of screen will then pop up, containing the following lines to greet you & acknowledge the application's successful run...!
"Successfully Transcribed as XLSX...!
Take a look at the 'Attendances Exported' folder...!
Built by HARISH KS | Jan 2021 | IT | 2019-23 PSG Tech"

The exported XLSX will precisely tell you the amount & percentage of time that every individual participant has spent inside (since observation began…!)
Columns in the exported XLSX ---> SNo, RollNo, Name, FirstSeenAt, %TimeInside, Hours, Minutes, Seconds
Additionally, there is a special feature built into the XLSX during transcription...!
The rows are coloured based on the '%TimeInside' factor, to help you quickly & easily sense an idea of the presence of every individual participant...!
%TimeInside >= 94		Green
%TimeInside >= 87		Yellow
%TimeInside >= 80		Orange
%TimeInside < 80		Red

Note - Your login credentials are saved in the "Autofill Defaults.txt" file, solely intended to improve your convenience & ease of use...!
They won't be copied or shared anywhere outside the "Autofill Defaults.txt" file which is stored locally on your own computer...
If the data on your computer is subject to be accessed by people, I suggest you to delete the "Autofill Defaults.txt" file regularly...!
I truly do respect & value your privacy very much (just as much as I value mine…!)

Warning 1 - Do NOT worry about the window rising up every time you attempt to minimize it into the taskbar, because it is designed to act that way!
Though you can't minimize it into the taskbar, you can of course open as many windows as you wish above it & hide it from your working screen...!
You will not be disturbed by it, even if you completely hide it from your screen, unless you minimize it down into the taskbar...!
The point here is that, it should be up & running, but it's not necessary that it should be visible on the screen...

Warning 2 - This will DEFINITELY NOT work for Google accounts with security measures enabled...! It will halt on the second login screen itself...!
Because, Google strictly restricts robotic programs to login using accounts of a specific category of security...
I guess, the 'two-step-verification' could be the factor causing it, but I'm not very sure about that...
This was tested on accounts belonging to two domains, 'gmail.com' and a customized university domain - the former restricted the bot from logging in
whereas the latter was just fine with a bot logging into the account & eventually participating in a GMeet session...!
I strongly recommend you NOT to compromise on the security of your account, risking it just for the sake of using this application...!
This is not the only way to fetch a GMeet session's attendance... You can find an alternative like the browser extension that people widely use...!

Built by HARISH KS | Jan 2021 | IT | 2019-23 PSG Tech
Mmm... It's Ok... Thank me later! ;)

Happy Automation!
~ Harish KS, Creator of RCB & Sneaky Attendance Transcription
