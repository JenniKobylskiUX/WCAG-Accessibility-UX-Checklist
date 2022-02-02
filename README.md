<h1>WCAG-Accessibility-UX-Checklist</h1>
Accessibility UX checklist to serve as a method for designers and developers to assess the WCAG compliance of their work.

<h2>UX Accessibility Checklist</h2>
WCAG Verification – 116 Questions  |  Cumulative list


<h3>1. Perceivable 	</h3>
Information and user interface components must be presentable to users in ways they can perceive.



1.1   Text alternatives-  Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as large print, braille, speech, symbols or simpler language.
Have we provided “alt text” alternatives for all images and data visualizations to a degree that information is not lost in non-visual representations of the page? ( Level A )
Have we provided “alt text” alternatives for all graphics like icons to a degree that information is not lost in non-visual representations of the page? ( Level A )


1.2   Time-based Media-  Provide alternatives for time-based media [such as video, sound, 
	slideshows, etc.]
Have we provided a transcript of prerecorded audio and video recordings? ( Level A )
Have we provided captions and descriptions for prerecorded audio and videos? ( Level A )
Are live captions available for live audio and video recordings? ( Level AA )
Have we provided audio recordings which describe in real-time the contents of all video recordings? 
( Level AA )
Do we have a video recording of an ASL interpreter translating our pre recorded media? ( Level AAA )
Have we provided an audio description of the prerecorded media that also includes implicit context that may not be understood through a language translation alone? ( Level AAA )
Have we provided a transcript or equivalent version of live video content? ( Level AAA )


1.3   Adaptable-  Create content that can be presented in different ways without losing the integrity and 
	context of the content.
Can we provide a simpler layout without losing information or structure? ( Level A )
Have we included a text description of our content that conveys implicit tone and meaning, even if it is not explicitly stated within that content? ( Level A )
Have we made the correct order of consuming our content obvious if the order of content is essential to understanding it? ( Level A )
Does the sequence of information as we reveal it make sense if we went through it in order? ( Level A )
Have we made sure to not use physical characteristics like color or location to explain how to accomplish a task? ( Level A )
Do we allow users to view our content in both landscape + portrait mode without distortion (unless one way or the other is essential)? ( Level AA )
Have we appropriately labeled our UI components so autofill can be used correctly? ( Level AA )
Have we labeled input fields to communicate what information users can enter and why?  ( Level AA )
Does our markup match what the UI element is so that support devices can apply the user’s customized preferences? ( Level AAA )


1.4   Distinguishable-  Make it easier for users to see and hear content including separating 
	foreground from background.


Can users tell the difference between the foreground and background of content? ( Level A )
Have we made sure that color is not the only way that we convey information in our content? ( Level A )
Can users easily increase or decrease audio if it lasts for more than three seconds? ( Level A )
Can all normal text colors be differentiated from their background color at a 4.5:1 ratio? ( Level AA )
Can all large text colors be differentiated from their background color at a 3:1 ratio? ( Level AA )
Can all UI/graphic colors be differentiated from their background color at a 3:1 ratio (unless they are disabled or logos)? ( Level AA )
Do all page elements render legibly when zoomed in at 200%? ( Level AA )
Have we made sure not to rely on images alone to share information (unless it is essential)? ( Level AA )
Can all normal text colors be differentiated from their background color at a 7:1 ratio? ( Level AAA )
Can all large text colors be differentiated from their background color at a 4.5:1 ratio? ( Level AAA )
Can all UI/graphic colors be differentiated from their background color at a 3:1 ratio (unless they are disabled or logos)? ( Level AA )
Can voices in audio be heard clearly and easily distinguished from background noise? ( Level AAA )
If we have included a block of text, have we given the user the ability to customize how they view it (color, alignment, line spacing, etc)? ( Level AAA )
Have we only used images of text (without alt text) for decoration, not sharing content?  ( Level AAA )
Have we made sure that a vertical scroll bar is not needed until we exceed 320px and a horizontal scroll bar is not needed until we exceed 256px? ( Level AA )
Can our content be viewed and understood without issues if the line height is 1.5 bigger than the font size? ( Level AA )
Can our content be viewed and understood without issues if the space between each line of text is at least double the font size? ( Level AA )
Can our content be viewed and understood without issues if the space between paragraphs is at least double the font size? ( Level AA )
Can our content be viewed and understood without issues if the space between letters is at least 0.12 times bigger than the font size? ( Level AA )
Can our content be viewed and understood without issues if the space between words is at least 0.16 times bigger than the font size? ( Level AA )
Are our UI components named as follows and are these states obvious to assistive devices? 
Active
Inactive
Focus
Disabled
Loading
Error

<h3> 2. Operable 	</h3>
User interface components and navigation must be operable.


2.1   Keyboard Only-  Make all functionality available from a keyboard.
Can users use a keyboard to access all content (as long as the path to get there is not important)? 
( Level A )
Can users navigate away from focused content using only a keyboard without getting stuck? ( Level A )
Can users use a keyboard to access all content no matter what? ( Level AAA )
Do we give the user the ability to turn hotkey shortcuts on and off? ( Level A )
Do keyboard hotkeys and standard shortcuts work properly within the interface? ( Level A )
2.2   Enough Time-  Provide users enough time to read and use content.
Can users adjust timing (re: slideshows, automated-scrolling, etc) if needed? ( Level A )
Are we giving users the ability to pause and restart automated content? ( Level A )
Do we give the user the ability to turn off motion animations if they start automatically? ( Level A )
Do we give users the ability to turn off motion animations if they last for more than five seconds? 
( Level A )
Do we give users the ability to stop or pause updates that begin automatically? ( Level A )
Do we give users the ability to signal that they need more time before a timeout? ( Level A )
Do we allow users to turn off timeouts unless they are necessary to security? ( Level A )
Is timing completely irrelevant for the user to fully engage with our content? ( Level AAA )
Do we only interrupt users from what they were doing in an emergency? ( Level AAA )
Do we give the user the ability to start where they left off after reauthenticating? ( Level AAA )
Do we preserve data as it was when the user is automatically logged out? ( Level AAA )


2.3   Seizures and Physical Reactions-  Do not design content in a way that is known to cause seizures or physical reactions.

Have we made sure none of our content blinks or flashes more than 3 times per second? ( Level A / Level AAA )
Have we given users the ability to turn off any animations that start as soon as they interact with them? ( Level AAA )
2.4   Navigable-  Provide ways to help users navigate, find content, and determine where they are.

Can we give redundancy cues and/or structural markup that alerts users of duplicated content? 
( Level A )
Do all pages have descriptive titles that differentiate them from others within navigation? ( Level A ) 
Do all headings describe the purpose of the page? ( Level A ) 
Does the order of tabs and information presented to those using a keyboard make sense? ( Level A )
Do all links read as clear descriptions of where they will navigate the user? ( Level A )
Are there multiple ways to navigate to a page within the system? ( Level AA )
Do all labels clearly describe the topic or purpose of the content they are labeling? ( Level AA )
Do our labels use the exact same words as the content they are describing? ( Level AA )
Is the focus indicator always available to those using a keyboard? ( Level AA )
Can the user verify their location within the interface (re: “sitemap” navigation)? ( Level AAA )
Do all links reveal their purpose to the user? ( Level AAA )
Do all links give additional descriptions about what the link’s content entails? ( Level AAA )
Have we consistently used the correct order of header hierarchy throughout the interface? 
( Level AAA )


2.5   Input Modalities-  Make it easier for users to operate functionality through various inputs beyond a keyboard.

Have we allowed the user to move their mouse in whatever pattern allows them to accomplish a task? 
( Level A )
Have we provided an alternative to swiping and other pointer based gestures? ( Level A )
Have we prioritized the “release” click of the mouse for the user to take action? ( Level A )
Are all buttons and graphic labels named as what they are? (re: “checkbox”, “notification,” etc) ( Level A )
Have we given users the ability to adjust/turn off motion input sensing ? (re: shake to erase) ( Level A )
Are our click targets at least 44px x 44px in size? ( Level AAA )
Have we enabled non-touch inputs even on devices where touch inputs are present? ( Level AAA )



Understandable
Information and the operation of the user interface must be understandable.



<h3> 3.1   Readable-  Make text content readable and understandable. 	</h3>


Has a default human language been programmed into markup? ( Level A )
Have we labeled what language is being used and when it changes to adjust vernacular? ( Level AA )
Have we labeled jargon and idioms within our content? ( Level AAA )
Do we offer a source that explains our abbreviations that's hosted internally or externally? ( Level AAA )
Have we presented content at a middle school reading level? ( Level AAA )
If our content is very complex, have we provided additional supporting materials to help users understand it at a middle school reading level? ( Level AAA )
Have we provided a mechanism to support correct pronunciation of terms not widely known? 
( Level AAA )


3.2   Predictable-  Make pages appear and operate in predictable ways.
Does content in a focus state remain exactly the same as when it’s in the default state? ( Level A )
Has the user been made aware that the interface will change when they input information prior to them doing so? ( Level A )
Are UI page elements in a standard, consistent place within the page’s layout? ( Level AA )
Is the sequence of those UI elements repeated consistently throughout the interface? ( Level AA )
Is the page and site navigation always in the same location on each page? ( Level AA )
Are our icons used consistently in the same context across the interface? ( Level AA )
Are the UI elements consistent with the behavior of standard UI elements? ( Level AA )
Are we allowing the user to decide when to take action instead of automatically doing it for them?
 ( Level AAA )
Do we give the user the ability to turn off all notifications until the end of the session?  ( Level AAA )


3.3   Input Assistance-  Help users avoid and correct mistakes.
Do we alert users immediately with an error message as soon as an error is detected? ( Level A )
Have we provided more than one cue that an error has occurred? ( Level A )
Are all required form fields clearly indicated to the user? ( Level A )
Are input fields always paired with directions that help the user decide what to enter?  ( Level A )
Do our alerts always include text, even if colors and/or graphics are also used in the notification?
 ( Level A )
Are our error messages as short and specific as possible? 
If an error is detected, have we offered a concise solution to fix the error? ( Level AA )
Have we allowed users to review and correct their submissions before submitting them? (Especially with legal commitments and financial transactions) ( Level AA )
Do we give the user the ability to immediately undo a mistake in any situation? ( Level AA )
Do we have a readily available system in place whenever a user needs help? ( Level AAA )
Have we created specific help text and options that allow the user to complete a task without losing track of where they are?
Do we allow users to change between devices when interacting with content on multiple devices during the same session?



Robust
Content must be robust enough that it can be interpreted by a wide variety of user agents, including assistive technologies.



<h3>4.1   Compatible-  Maximize compatibility with current and future user agents, including assistive technologies. 	</h3>


Does all content that uses a markup language have complete start and end tags? ( Level A )
Does all of our markup include only one attribution (no duplicates)? ( Level A )
Are all HTML elements correctly nested according to standard use?
Can the name and role of all UI elements be easily detected by supportive technology? ( Level A )
Can all of our status messages be automatically received and interpreted by supportive technology (even if they are not the user’s current focus)? ( Level AA )


