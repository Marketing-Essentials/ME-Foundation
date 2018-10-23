# M.E. Foundation

## A super stripped-down WordPress starter theme for the Marketing Essentials, LLC developers. 


#### How to use M.E. Foundation?
Download or clone into your `/wp-content/themes/` folder and activate the theme in the WordPress admin in `Appearance > Themes`. 

**Note:** You will need to use a pre-processor to compile `.scss` (Sass) into `CSS`. We recommend [CodeKit](https://codekitapp.com). Just drop your theme into CodeKit and you're all set. No configuration necessary. We love CodeKit `<>`.

From there, fire up your favorite text editor, customize the default styles to match the custom mock design, and that's it!


### ⭐️ Why M.E. Foundation?
There's no bloat or unnecessary fluff that comes with many pre-built themes so you can add in what you need and remove what you don't. Yet, it comes with some smart defaults that facilitate getting your project up and running quickly: CSS Reset, modular scss, typography, a user agent detection script, page slug body classes, built in page-navi, template parts and custom page/archive/taxonomy templates. This is the perfect starting place for any custom-designed WordPress projects.

M.E. Foundation evolved out of Plate. Plate evolved out of the amazing [Bones](https://themble.com/bones/) starter theme by Eddie Machado.

We found that we were commonly making the same changes every time we started a new project for our clients, so we decided to fork Plate and make it unique to our organization and how we develop sites. We now use M.E. Foundation for every single WordPress project.


### ❔ FAQ
**Should I update M.E. Foundation with existing projects?**<br />
In short, no. Each version of M.E. Foundation should be viewed as a moment in time. Future updates may work differently or break your theme. Once you've included a particular version in your project, stick with that version or use a newer version as a separate theme. This is how Bones worked and how Plate worked and we decided to keep this strategy when updating so that it can evolve over time without worrying about backwards compatibility. You can always download a previous version of Plate from the [Releases page](https://github.com/joshuaiz/plate/releases).


**I tested it with Theme Check and there are errors. What should I do?**<br />
[Theme Check](https://wordpress.org/plugins/theme-check/) is ideal if you are trying to get your theme validated for release on WordPress.org. That said, we use Theme Check and test before every GitHub release to see if we have any egregious errors in Plate. Mind you, Plate was created for our studio and not (necessarily) for general release. With that in mind, there are some things that will fail the check like not having `<php wp_link_pages(); ?>` which we don't ever use as well as having a CPT plugin template included. We're ok with those errors and as long as they don't bother you, you can safely ignore.

### ⚡️ Other Stuff
Maintained by Jenna Schultz.

With help from Tyler Louth & Kyle Johnson.

License: WTFPL
License URI: http://sam.zoy.org/wtfpl/

Do whatever you want. Freedom, baby.

#### ✨ Special Thanks to:
Eddie Machado — all credit is due to him and the original Bones collaborators: Paul Irish, Yoast, Andrew Rogers, David Dellanave and others. 

Also, credit goes to joshuaiz, who took bones and transformed it into Plate.
