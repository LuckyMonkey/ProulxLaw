# Proulx Law Offices

* [Website](http://jplaw.me/)

* [Development Site](https://luckymonkey.github.io/proulxlaw/)

## What this is
A website to help provide clients and attorneys with access to resources, help with thier bankrupcy situation, and most importantly provide a way for them to establish contact with Proulx Law Offices.

## Getting Started
Website contains 3 pages, page depth is 1, and 5 links to exterior web, 2 websites that are resources and steps to starting the bankrupcy process, and 3 portals for Proulx Law Offices social media pages.

### Links
* [Facebook Profile](https://facebook.com/jplaw.me/)
* [LinkedIn Profile](https://linkedin.com/in/jenny-louise-proulx-721a631b/)
* [Avvo Profile](https://avvo.com/attorneys/03101-nh-jenny-proulx-4303376.html)

* [Get Free Credit Reports](https://avvo.com/attorneys/03101-nh-jenny-proulx-4303376.html)Get free Credit Reports
* [Take credit counciling course](https://avvo.com/attorneys/03101-nh-jenny-proulx-4303376.html)

### Pages
Homepage - Landing page, giving information about law firm, and providing links for both Individuals and Attorneys
Individuals - Provides two links
Attorneys - Provides basic disclaimer and form, form is expanded from the individuals one.

### Goals
Responsive webpage - One that works on both Mobile Devices
and Desktop Computers

Internet Business Card - Provide Contact Details for Proulx Law Offices

Internet Contact Form - Provide forms for clients and attorneys to contact Proulx Law Offices

Social Media Hub - Provide Portals to Social Media pages and link them together, in the future allow content to be linked back to webpage from a feed.

### Page Header and Footer Code
The purpose of posting this here is because each page operates as it's own independant html file and not importing content from another source via PHP (yet). Each change done to either the header or footer of this site must be applied to each page individually, as well as updated here.

```
<header class='hibiscus'>
    <a href='index.html'><h1><i class='fa fa-home'></i>&nbsp;Proulx Law Offices</h1></a>
    <nav>
        <a href='http://facebook.com/jplaw.me'>
            <i class="fa fa-facebook-square fa-2x"></i>
        </a>
        <a href='https://linkedin.com/in/jenny-louise-proulx-721a631b/'>
            <i class="fa fa-linkedin-square fa-2x"></i>
        </a>
        <a href='https://avvo.com/attorneys/02145-ma-jenny-proulx-4303376.html'>
            <img alt="Find a Lawyer" width="60" height="27" src="https://avvo.com/assets/content/logotiny1.gif" />
        </a>
    </nav>
</header>
```

```
<section class='hibiscus' id='footer'>
    <ul class='fa-ul'>
        <li class='hide'>Jenny Proulx</li>
        <li><strong>Proulx Law Offices</strong></li>
        <li>1087 Elm Street, Suite 223</li>
        <li>Manchester, New Hampshire</li>
        <li>03101 USA</li>
    </ul>
    <ul class='fa-ul'>
       <br />
        <li><i class='fa fa-li fa-phone'></i>(MA) +1 (617) 335-8145 </li>
        <li><i class='fa fa-li fa-phone'></i>(NH) +1 (603) 731-3965 </li>
        <li><i class='fa fa-li fa-fax'></i><sup>(FAX)</sup>&nbsp;&nbsp;+1 (617) 507-7693</li>
    </ul>
    <ul class='fa-ul'>
       <br />
        <li><i class='fa fa-li fa-facebook'></i> <a href="http://facebook.com/jplaw.me">Facebook</a></li>
        <li><i class='fa fa-li fa-linkedin'></i> <a href="https://linkedin.com/in/jenny-louise-proulx-721a631b/">LinkedIn</a></li>
        <li><i class='fa fa-li fa-gavel'></i> <a href="https://avvo.com/attorneys/02145-ma-jenny-proulx-4303376.html">Avvo</a></li>
    </ul>
    <ul class='fa-ul'>
       <br />
        <li><i class="fa fa-home fa-li"></i><a href="index.html">Home</a></li>
        <li><i class="fa fa-user fa-li"></i><a href="individuals.html">For Individuals</a></li>
        <li><i class="fa fa-handshake-o fa-li"></i><a href="attorneys.html">For Attorneys</a></li>
        </ul>
</section>
```


## Dependancies
* [GoogleFonts](http://fonts.google.com) - Custom pretty fonts provided with speed from Google. (Fonts used 'Open Sans' & 'Comfortaa' )

* [Normalize.css](https://necolas.github.io/normalize.css/) - Makes browsers render all elements more consistently.

* [jQuery](http://jquery.com) - Javascript library used for email form Validation.

* [FontAwesome](http://fontawesome.com) - Generic Icons compiled into a font, used througout the website.

* [MapGlyphs](http://mapglyphs.com/) - Map vectors compiled into a font, used for the shapes of the states on the homepage.

* [FormBakery](http://formbakery.com) - Used to create PHP email form.

## Authors
* **Charles Redden**
* **Jenny Proulx**

## Contributing
Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests or reporting issues to us.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
