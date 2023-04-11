# IMPORTANT!

This is an updated version of software developed by [Richard Kreisman](https://github.com/richardkriesman/), and all respective credits should go to them.

Late in the 2022 school year, I was reached out to by my school's IT administration about a possible issue that they had with "BHSPromApp", and I told them I would look into it. Upon doing so, I realized that the fixes that were needed were more than within my scope of knowledge, and I was able to quickly resolve them, returning to them an updated version of the application, that both included patches for the issues they encountered, along with additional features for managing accounts that had been registered. These features primarily focused on changing the method in which a user's roles were selected, instead of a promotion system, they were instead replaced with a dropdown menu that allows an admin to select the specific role to promote a user to instead of individual promotions.

The IT admins would then reach back out to me again late in the 2023 school year, about a very small change that they had seen requested by one of the school administrators. This change was simply rearranging the order of some text when retrieved from the district's databases.

In summary, the changes I have made over the ~year that I have had around this project, I have made some minor improvements to an otherwise already capable application, and I highly recommend that you look into the original project by [Richard Kriesman](https://github.com/richardkriesman/).

# BHSPromApp

BHSPromApp is a web-based registration, finance, and seating assignment system for events, created for L.D. Bell High School to use for their senior prom. I created this as a volunteer project during my Junior and Senior years of high school there. Yes, it's PHP. Yes, it's janky. Yes, the code is spaghetti. But I'm still putting it up here for reasons. Maybe I'll actually pick it up and mess with it some time.

BHSPromApp can help you:
 - Register attendees and print tickets
 - Provide seating assignments
 - Track and report event revenue
 
 BHSPromApp supports multiple events and live collaboration, as well as Active Directory integration (for very specific setups). It supports Chrome, Firefox, and IE11 and up. Due to circumstances that prevented the use of a dedicated database server, SQLite is used for the database. It should work fine for a few people, but will definitely be a bottleneck in a large scale deployment.

### Installation

Installation is pretty simple process. Throw it on a PHP server, give write access to the "database" folder, fill out the configuration file in "include/config.inc.php", and away you go. Although frankly, this may not be much use to you. As I said previously, it was made specifically for the high school I went to, and was designed to meet its specific requirements.

### License

If you want to try it out or work on it, feel free to. It's licensed under the GPLv3, so you can use it for whatever purpose you want as long as it's not incorporated into any other commercial software.

**Notice:** BHSPromApp uses BarcodePHP (now Barcode Bakery) for generating barcodes, and a license is required for commerical use.
