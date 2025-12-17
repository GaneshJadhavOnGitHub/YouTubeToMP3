# YouTubeToMP3
Program downloads and saves MP3 from Youtube URL. 

NonCommercial — You should not use the material for commercial purposes.

** YouTube To MP3
---------------------

** Most Important :- 
----------------------

This program is for educational purpose only and please do not use this program for commercial 
purpose. 

Because , 
 
According to Youtube's terms of use 

'You are not allowed to [...] access, reproduce, download, distribute, transmit, 
broadcast, display, sell, license, alter, modify or otherwise use any part of 
the Service or any Content except: (a) as expressly authorized by the Service; 
or (b) with prior written permission from YouTube and, if applicable, 
the respective rights holders.'

---------------------------------------------------------------------------------------------------

Program Requirements
---------------------------------------------------------------------------------------------------
Operating System  - Windows 10 Pro Version 21H1 (OS Build 19043.1645)

Dot Net Framework - 4.7.2

---------------------------------------------------------------------------------------------------


External Libraries Used
----------------------------

1. NReco.VideoConverter 
   Version:-  1.1.2.0   
   
   Runtime Version:-  v2.0.50727

   NReco Video Converter component for C#.NET [wrapper for ffmpeg (Fast Forward mpeg) command line tool]. 
   Used to encodes the downloaded audio stream to MP3 with 128 KBPS Bitrate.

2. Gress 
   Version:-  1.2.0.0   
   
   Runtime Version:-  v4.0.30319

  Gress library is used to report download progress.
   
3. YoutubeExplode
   Version:-  6.0.5.0   
   
   Runtime Version:-  v4.0.30319

   YoutubeExplode is used to download video/audio streams.

5. AngleSharp
   Version:-  0.14.0.0  
   
   Runtime Version:-  v4.0.30319

   AngleSharp is a .NET parser for HTML, XML and it's used by YoutubeExplode
   for parsing YouTube's web pages to discover stream information.

   
   Note : Install Dependencies via nuget package manager console.

---------------------------------------------------------------------------------------------------


Description of the program 
---------------------------------------------------------------------------------------------------

Input to the Program :- Valid Youtube Video URL

Output :- MP3 Audio File 

The program extracts and saves the Audio stream of the given Video in MP3 format.

Output Screenshot :- 
--------------------


![YoutubeToMp3-Output](https://user-images.githubusercontent.com/86361080/183070486-3b4a6f2f-4611-4a68-969e-0106b3fb1039.png)


Working of the Program :- 
--------------------------

1. Validates the given URL, if it is not a valid URL it displays error message.

2. Prompts user for the name of the MP3 File, the MP3 file is saved with this name.

3. Shows the thumbnail image of the video of which MP3 is being downloaded.

4. Shows size of the audio stream being downloaded.

5. Extracts Audio from given Video and encodes it in MP3 Format with 128KBPS Bitrate.

6. The encoded MP3 file does not contain any cover image and tags 
   except artist tag which has the value 'Downloaded_From_Youtube'.

7. Shows realtime download progress percentage.

8. Continuously checks the connectivity to the internet and displays error if connection is lost.
---------------------------------------------------------------------------------------------------


Glossary 
---------------

Bitrate :-  Bitrate is the number of bits (or data) that are processed per unit of time.

Encode  :-  Encoding is the process of changing digital audio from one format to another.

KBPS    :-  Kilobits per second.

MP3     :-  MPEG Layer 3 or Moving Picture Experts Group Layer 3
            MP3 is an audio file format where audio is saved in a compressed audio format.
            It is developed by the Moving Picture Experts Group (MPEG) 
            that uses "Layer 3" audio compression (MP3). 

Stream  :-  A stream is a source or sink of data, usually individual bytes or characters. 
            Streams are an abstraction used when reading or writing files.

URL     :-  Uniform Resource Locator 
            A URL (Uniform Resource Locator) is a unique identifier used to locate a resource
            on the Internet.

---------------------------------------------------------------------------------------------------




