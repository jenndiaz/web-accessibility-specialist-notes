# WCAG 2.2 AAA Guidelines 
Since most of my work prioritizes A and AA findings, I am reviewing AAA findings in this document. 

Synchronized media: Time based media paired with another format. For example a video with synchronized audio track and captions or a video with interactive elements like clickable links at certain times. 

User agent: Any software that retreives and presents web content for users; browsers, media players, assistive technologies. 

## Perceivable 

### 1.2.6 Sign Language (Prerecorded) 
Sign Language interpretation is provided for all prerecorded audio content in synchronized media.
Some Deaf people may not be able to read or comprehend captions as well as they could sign language. Sign Language translations gives these people access to synchronized media. 

### 1.2.7 Extended Audio Description (Prerecorded) 
Where pauses in foreground audio are insufficeint to allow audio descriptions to convey the sense of the video, extended audio description is provided for all prerecored video content in synchronized media. 

### 1.2.8 Media Alternative (Prerecorded) 
An alternative for time based media is provided for all prerecorded synchronized media and for all prerecorded video only media. 
Text equivelents for all content videdos such as transcripts. 

### 1.2.9 Audio-only (Live)
An alternative for time based media that presents equivalent information for live audio only content is provided. 
Text equivelents for live audio only content, such as a transcript or planned script. 

## Operable 

### 2.1.3 Keyboard (No Exception) 
All functionaility of content is operable through a keyboard interface without requring specific timing for individual keystrokes. 
Same as 2.1.1 Keyboard but without the exceptions. 

### 2.2.3 No Timing 
Timing is not an essential part of the event or activity presented by the content except for non-interactive synchronized media and real-time events. 
Differs from Level 1 in that the only exception is for real time events. 

### 2.2.4 Interruptions 
Interruptions can be postponed or suppresssed by the user, except interruptions involving an emergency. 
So that updates do not distract users. 

### 2.2.5 Re-authenticating 
When an authentication session expires, the user can continue the activity without loss of data after re-authenticating. 
Users are able to continue where they left off in the event they are logged out.

### 2.2.6 Timeouts 
Users are warned of the duration of any user inactivity that could cause data loss, unless the data is preserved for more than 20 hours when the user does not take any actions. Tell users how long their session can be inactive before they may lose information. 

### 2.3.2 Three Flashes
Web pages do not contain anything that flashes more than three times in any one second period. While 2.3.1 allows flashing if it is dim enough or has a small enough area, 2.3.2 does not allow it at all. 

### 2.3.3 Animation from Interactions 
Motion animation trigger by interaction can be disabled, unless the animation is essential to the functionaility or the information being conveyed. Allow users to set their own preferences for motion in response to users actions. 

### 2.4.8 Location 
Information about the users location with in a site is avaliable. Such as breadcrumbs, a sitemap, or navigation bar. 

### 2.4.9 Link Purpose (Link Only)
A mechanism is avaliable to allow the purpose of each link to be identified from link text alone. Idealy, this is descriptive link text. 

### 2.4.10 Section Headings 
Section headings are used to organize content. When organized into sections, pages should have headings. 

### 2.4.12 Focus Not Obscured (Enhanced) 
When a UI component recieve keyboard focus, no part of the component is hidden by author created content. Such as a sticky header that partically covers a component recieve focus. More specific than 2.4.11 which allows for partially hidden components. 

### 2.4.13 Focus Apperence 
When the keyboard focus indicator is visslbe, an area of the focus indicators is atleast 2 CSS pixel think perimeter and have a contrast ratio of atleast 3:1 between focused and focused states. 

### 2.5.5 Target Size (Enhanced) 
The size of the target for pointer inputs is atleast 44 by 44 pixels. Exceptions: equivelent link or control exists that meets the minimum, the target in line with text, size of the target is determined by the user agent, the presentationl is essential. 
As opposed to 2.5.8 where the minimum target size is 24 by 24 pixels. 

### 2.5.6 Concurrent Input Mechanisms 
Web content does not restrict use of input modalities avaliable on a platform except where the restriction is essential, such as required to ensure the security of the content or respecting user settings. For example mobile apps shouldn't resricit the use of a keyboard, mouse, or switch device.  

## Understandable

### 3.1.3 Unusual Words 
A mechanism is avaliable for IDing specific definition of words or phrases used in an usnual or restricted way, such as idioms and jargon.

### 3.1.4 Abbreviations 
A mechanism is avaliable for IDing the exapnded version or meaning of abbreviations is avaliable. 

### 3.1.5 Reading Level 
When text requires reading ability more advances than lower secoindary level after removal of proper names and titles, supplemental content, or a version that does not require higher reading ability is avaliable. 

### 3.1.6 Pronunciation 
A mechanism is avaliable for idenfitying specific pronounication or words where meaning of the words in context is ambiguous without knowing the pronounciation. 

### 3.2.5 Change on Request 
Changes of context are initiated only by user request or a mechanism is avaliable to turn off such changes. 

### 3.3.5 Help 
Help is avaliable related to the function currently being preformed. Such as spell check or a help link. 

### 3.3.6 Error Prevention (All) 
For pages that require the user to submit information at least one of the following is true: Submissions are reversible, check is checked for errors, and a mechanism for reviewing before submission. 

### 3.3.9 Accessible Authentication (Enhanced) 
A cognitive function test is not required for any step in an authentication process unless that steps provides one of the following: an alternative methods or a mechanism to avalaible to assist in completeing the function test. 
