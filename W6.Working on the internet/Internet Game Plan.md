# Part I: ["The Stack"](https://prezi.com/view/KyLPNTtqaHORpCP6K2R6/)
Note that the presentation linked above  works well in Chrome, but not always in Firefox. Your milelage may vary.

Have you ever wondered how systems and internet services are organized?  Whether you interact with a local machine or over the internet your communications flow through layers of dependencies referred to in IT as "the stack".  Why should you care?  It's true that you can use the internet without this nuanced understanding, but online work can benefit from deeper knowledge, especially when you are working through issues where things have gone awry. Michelle will review the general structure of these architectures and allow from questions throughout.  
  
# Part II: Making Use of the Stack: Web  Publishing & Hosting  
  
## Publishing Platforms
  
### [Scalar](https://scalar.me/anvc/scalar/)
[User’s Guide/Documentation](https://scalar.usc.edu/works/guide2/index)  
* Designed for publishing digital scholarly essays and books  
* Allows you to embed and annotate images, documents, audio, and/or video objects.  

**Owner/Developer**: The Alliance for Networking Visual Culture (a scholarly association)  
**Hosting**: Free hosting at scalar.usc.edu OR host at your own domain with Reclaim Hosting (See below).  
  
Examples:  
* [Claude McKay’s Early Poetry (1911-1922): A Digital Collection](https://scalar.lehigh.edu/mckay/index) (Amardeep Singh)  
* [A Photographic History of Oregon State University](http://photohistory.oregonstate.edu/works/photo-history/index)(Larry Landis with OSU Digital Publishing)  
This site, unlike the other Scalar examples, is primarily image-based. Note the use of tags (how do tags change the user’s experience?) and multiple pathways through the exhibit.  
* [Shining Lights: Magic Lanterns & The Missionary Movement, 1839-1868](http://scalar.maryborgoton.com/shininglights/index)(Mary Borgo Ton)  
This site comprises Ton’s dissertation in the English Dept. at Indiana University. The topic includes Film Studies. Look for the ways that Ton leverages the digital format to provide embedded video illustrations and demonstrations -- to produce scholarly output that would not be possible in an analog format.  
* [How Convenient are our Conveniences?: The demise of underground facilities in Dunedin (New Zealand) 1910s-1980s](https://scalar.usc.edu/works/conveniences/index) (Alison Breese)  
This site comprises Breese’s entirely digital thesis for her MA at University of Otago. The topic includes public architecture. Look for the ways that Breese makes use of digital illustrations. (Note the timeline and maps seem to be broken the last time I checked.)  

### [Omeka Classic](https://omeka.org/classic/)  

[User Manual / Documentation](https://omeka.org/classic/docs/)  
Tutorial: [Up and Running with Omeka.net](https://programminghistorian.org/en/lessons/up-and-running-with-omeka) by Miriam Posner, *The Programming Historian*  (SKIP the part on signing up for Omeka.net.)  
Tutorial: [Creating an Omeka Exhibit](https://programminghistorian.org/en/lessons/creating-an-omeka-exhibit) by Miriam Posner & Megan R. Brett, *The Programming Historian*   

•	Designed for managing collections of digital objects (images, audio, video) and their metadata.  
•	Allows you to create displays or digital exhibits of your digital objects.  
  
**Owner/Developer**: Roy Rosenzweig Center for History and New Media at George Washington University.  
**Hosting**: Each Omeka instance must be hosted somewhere. The Cornell CoLab can host it for you for free on our site OR you can host your instance on your own site and your own domain via Reclaim Hosting (see below). (What I do not recommend is hosting your via Omeka.net, which collects a fee, but does not allow full control of your site and plug-ins.)  

**Examples:**  
* [[Japanese Modernism Across Media](https://ds-omeka.haverford.edu/japanesemodernism/home) (Students of Bryn Mawr & Haverford Colleges
A collection of 11 exhibits which use different approaches to presenting material. Note the embedded Neatline components in some of them.  
* [Wearing Gay History](http://wearinggayhistory.com/) (Eric Gonzaba & Collaborators)
Note that you can browse the entire collection of all the digital items via the “T-shirts” tab, and examine curated exhibits via the “Exhibits” tab.  
* [Colored Conventions](https://coloredconventions.org/)  
Hub for collections, exhibits, visualizations, and coordinated information about a large multi-institutional research project on the history of 19th-century Black abolition and civil rights movements.  

### [Wordpress](https://wordpress.org/)
[User Manual / Documentation](https://wordpress.org/support/)  

•	An open-source content management system (CMS) used by many different types of websites.  

**Owner / Developer**: Wordpress Foundation
**Hosting**: Each Wordpress instance must be hosted. You can get free hosting at Wordpress.com, or, for more flexibility and functionality, you can host your own instance on your own domain (see below).  
  
**Examples**  
* [De raptu meo](http://chaumpaigne.org/) (Anna Waymack, Cornell Ph.D. candidate in Medieval Studies)
* [Parthian Sources](https://parthiansources.com/) (Jake Nabel, Cornell SGFDH alum, now prof of Classics at Penn State)  
* [Angelenos Incarcerated: The LA County Jail Oral History Project](https://angelenosincarcerated.org/) (Joanne Decaro)  
The platform is Wordpress. There is also a Neatline map embedded.  



## Hosting Your Web Site: Static vs. Dynamic  

The components of a basic website are HTML, CSS, & JavaScript (JS). All of these languages operate on the *client side.* A static site is one that uses just these three languages, and is rendered the same each time. A more complicated web site, called a dynamic web site, relies on a content management system (see below), and renders each web page as it is called up by the "client" (your own personal computer). 

### Static Web Sites 

If you need a static web site that is secure and easy to maintain, the software Jekyll and the host [GitHub Pages](https://pages.github.com/) might be a good option. There's a little bit of set up to learn, but once you're set up, your pages are straight-forward to write and maintain. 

*Programming Historian* has [a good tutorial on setting up a Jekyll site hosted by GitHub Pages](https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages) (by Amanda Visconti).  

GitHub Pages is a no-fee host. It's free to use. However, it's good to know that GitHub is a commercial company owned by Microsoft, and can change its terms of service at any time. The good news is that Jekyll makes it easy to export and transport your site to a different host if you want to, for any reason. 

Examples of web sites built with Jekyll (some hosted on GitHub Pages):  
* [New York Data Carpentries Library Consortium](https://nydclc.github.io/)  
* [Digital Space and Place](https://cblevins.github.io/sp18-space-place/) (a course site by Cameron Blevins)  
* [UN World Statistics Day](https://worldstatisticsday.org/)  
* [Leaflet for R](https://rstudio.github.io/leaflet/)  
* [Collections as Data: Part to Whole](https://collectionsasdata.github.io/part2whole/)  

Anytime you see the domain github.io, that page is built with Jekyll and *hosted* on GitHub Pages.

### Dynamic Web Sites  

If your web site needs a content management system, or a relational database, or other *client-side* programming, you will need a place to host it. You have two basic options:

1. Lease your own space. Have full access to the back end. Install whatever you want there.  
  * In most cases, I recommend [Reclaim Hosting](https://reclaimhosting.com/shared-hosting/). It's designed for scholars, has fantastic technical support, and makes it really easy to install your own instance(s) of Wordpress, Omeka, Scalar, mySQL, and many more platforms. You can also start from scratch and host any HTML, CSS, and/or JS that you write (or borrow/adapt) here. Security and back ups are covered for you. You can register any domain name you like (or move an existing one over). Cost for a personal plan is $30/year.  
  * Some useful support tutorials:  
  [Installing Omeka on Reclaim Hosting](https://community.reclaimhosting.com/t/installing-omeka-classic-on-reclaim-hosting/193)  
     [Installing PlugIns (like Neatline) on Reclaim Hosting](https://community.reclaimhosting.com/t/uploading-plugins-to-omeka/195)  
     [ImageMagick: Important Tip for Setting up your own instance of Omeka](https://community.reclaimhosting.com/t/imagemagick-in-omeka-classic/230)  
  * In a few cases you might want to install something that Reclaim doesn't support easily. One example is PostGIS, a spatial relational database software. In that case you would need to get some developer cloud space at a host like [Digital Ocean](https://www.digitalocean.com/).  
  
2. Use some of the the CoLab's space.  
  * The CoLab has an organizational account (100 GB) through Reclaim. If you're not ready to buy your own space, or you just want a temporary space to experiement, you can use some of it for your own installation of Omeka, Scalar, Wordpress, or another software package. The domain You won't have your own access to the backend of the server itself (so you can't write your code from scratch), but you *can* access the back end of whatever software installation you have are using, and if/when you're ready to migrate it over to your own Reclaim (or other) space, you can. The domain name will be cornellcolab.net. 
  * CoLab space is also a good solution if you're teaching a class and your students need space for their projects. (See undergrad examples below.) You can talk to Eliza anytime about getting space for student assignments.  
  
### When You Just Want to Share Your Code  

Let's say you have data or software that you've written and want to make available to others. The standard place to do that is GitHub. If you want, you can also produce a static web site in GitHub Pages that links to your code repository.  

Here are examples of digital projects hosted on GitHub:  
* La Gaceta de la Habana  
* Intertext  

Here is an example of a GitHub Pages front page for a series of code repositories hosted on GitHub:  
* [Data and Visualization Workshops at NCSU](https://ncsu-libraries.github.io/data-viz-workshops/)  
