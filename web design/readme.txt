This is the README file for the CSR Originals website. This document represents a website for CSR Originals, a Tech organization focused on charity and donations. The code's arrangement and framework are detailed below.

There are several sections and features in the csroriginals.html and csr_styles.css documents:

1)Head Section: includes metadata, character set, viewport settings, links to external CSS stylesheets, favicon, and the Page title.

2)The header includes navigation links to "Home," "Products," "About," and "Charity." A search function is also included.

3)Body Section: This section contains the CSR originals website primary content.

4)Header: Shows the name, logo, and navigation links of CSR originals website.

5)Video: Features a introduction video (source: youtube/apple) with autoplay and mute options.

6)Bestsellers & Products: Displays a table with the  photos, names and prices of three mobile products.

7)About: Provides details about the CSR organization's goal and mission.

8)Message from the Ambassador: contains an image and an audio message of the Ambassador of CSR originals website.

9)Customer Reviews: Displays customer reviews of CSR originals website along with video clips.

10)Footer: Includes contact details such as phone, email, Instagram contact links and copyright information of CSR originals are provided in the footer. 


Explanation of the HTML elements in csroriginals.html, charity.html, csr_styles.css pages and tags mentioned in CSR originals website, used in the provided code:

1)Favicon (<link rel="icon">)
Favicon () Explanation: Specifies the icon (favicon) that appears in the browser's tab. 
Example in Code: <link rel="icon" type="image/x-icon" href="img/favicon1.jpg">


2)Table (<table>, <tr>, <td>)
Explanation: Constructs a table to display data of Bestbellers and products. 
Example in Code: <tr>
                <td><b></b></td>
                </tr>

3)Form (<form>)
Explanation: Creates a form for csroriginals.html and  Charity.html to collect user input and details.

4)Images (<img>)
Explanation:  adding images on the CSR Originals web page.
Example in Code: <img id="favicon" src="img/favicon1.jpg" alt="CSR originals">

5)Hyperlink (<a>)
Explanation:  links that users can click to access other websites or resources.

6)Button (<input type="submit">, <button>)
Explanation: Creates buttons that is used to submit information.

7)Audio (<audio>, <source>)
Explanation: adding audio content on the CSR Originals web page.
Example in Code:
<audio controls>
    <source src="music/speech.mp3" type="audio/mpeg">
</audio>

8)Video (<video>, <source>)
Explanation:  adding video content on the CSR Originals web page.
Example in Code:
<video style="width: 100%; height: auto;" width="100%" height="100%" src="img/promo1.mp4" muted autoplay loop></video>

9)Header (<header>)
Explanation:  Section includes logos, headings, and navigation menus.

10)Footer (<footer>)
Explanation: Describes the CSR Originals web page's footer, includes contact information and copyright information of the ambassador.

11) Summary (<summary>)
Explanation: Provides a summary of CSR Originals web page within a <details> element.
Example in Code: section id="About"><br><br>
        <h2>About</h2>
        <details>
            <p>You Shop. You Save. We Give.</p>
        <summary> ..</summary>
        </details>

12)Menu - implemented Navigation bar for webpage which helps to  navigate across the website.
Explanation: Menu or Navigation bar are designed using links such as <ul>, <ol>, <li> and other HTML elements. 

13)tel for Contact Information (Hyperlink)
Explanation: Provided a phone number is a clickable link that, when clicked, redirects and initiates a phone call.
Example in Code: <a href="tel:+1(617)401-5368">...</a>

14)mailto for Contact Information (Hyperlink)
Explanation: Provided an email address is a clickable link that, when clicked, redirects and opens the mail box to send an email.
Example in Code: <a href="mailto:reddysathwik44@gmail.com">...</a>


CSS:
"csr_style.css" provided enables styling of the HTML elements in csroriginals.html and charity.html 

Tags, Classes, and ID selectors:

tags: body, h1, h2, p, ul, li
tags: h2, header, ul, p, div, table, tr, td, th, input, audio, video, label
Class selectors: .searchBox, .topnav, .phoneimg, .amb, .process_donation, .reviews, .customers
ID selectors: #favicon, header h1, #About, #ambass1, #customers, #stars

Other important tags:

<!DOCTYPE html>: Declares the document type and HTML version.

<html lang="en">: Specifies the language of the document as English.

<head>: includes metadata and external resource links.

<body>: The main content of the web page.

<header>: Contains the website's header, including logo, navigation links, and search form.

<meta name="viewport"> for responsive design

<div id="Bestsellers">: A section for showcasing bestsellers and products.

<h2>: Subheading for the products section.

<table>: Creates an HTML table for product showcase.

<tr>: Defines table rows.

<td>: Defines table cells.

<a>: Creates links to product pages.

<img>: Displays  images.

<section id="About">: A section which has  information about the organization.

<p>: Paragraph describing the organization's mission.

<summary>: Provides a summary of the organization's activities.

<section id="ambass1">: A section for a message from the ambassador.

<img>: Displays an image of the ambassador.

<audio>: Embeds an audio player for the ambassador's message.

<source>: Specifies the audio source file.

<section id="customers">: A section for customer reviews and testimonials.

<footer>: Contains copyright information and contact details.

<a>: Links to Instagram, phone, and email contact options.
