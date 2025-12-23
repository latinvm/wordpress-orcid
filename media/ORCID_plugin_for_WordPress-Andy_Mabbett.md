# ORCID plugin for WordPress

By Andy Mabbett
Posted on May 22, 2014

Source: [Pigs on the Wing](https://pigsonthewing.org.uk/orcid-plugin-for-wordpress/)

---

ORCID – the Open Research Contributor ID – is an identifier for contributors to academic and other works; think ISBN for books, or DOI for papers; and I've been working with them for over a year, on their works metadata working group; as an outreach ambassador; and integrating ORCID in Wikipedia and Wikidata.

At an ORCID outreach event and hackathon this week, at the University of Illinois, Chicago, Roy Boverhof – sponsored by Elsevier – coded an ORCID plug-in for WordPress (his first WordPress plug-in!), to my concept, requirements and hand-drawn wireframe.

It allows WordPress authors to add their ORCID to their user profile, which can then be displayed on their posts. See mine, "0000-0001-5882-6823", at the foot of this post; and Roy's in a comment below.

It also allows commenters to optionally enter their ORCID in the comment form, with a tick-box to approve comments with a valid ORCID. See my ORCID displayed, below, under my name on the first comment.

The plug-in is available from Roy's GitHub repository, and can be installed via Plugins > Add New in the WordPress interface.

This is still a beta. You may need to delete any earlier version first. What still needs to be done includes:

- Documentation (what would you like to know?)
- Calculating and verifying check-digits

We came second in the hackathon competition!

---

## Updates

**May 28, 2014:** Various improvements.

**May 28, 2014:** Version 0.5

**December 22, 2025:** After more than a decade, version 1.0 has been released with significant improvements, new features and updates.

---

## Selected Comments

**Roy Boverhof** - May 22, 2014
Testing... ORCID: 0000-0002-7299-680X

**Roy Boverhof** - May 28, 2014
I have refactored the plugin into a class, which makes it a lot more maintainable.

**Martin Fenner** - May 23, 2014
Nice, but rather than making people type a 16-digit number, wouldn't it be better to use OAuth? That way you can be sure that people provide the correct ORCID. You might also want to provide the plugin via the WordPress plugins directory for easier installation.

**Philip John** - May 22, 2014
Nice one Roy! I've submitted a pull request to tidy up the structure a bit and have a good idea for improving a few more things. Looking forward to helping improve it!

**Vincent Pai** - December 17, 2025
Hi Andy, this plugin doesn't seem to have any activity since May 2014. Do you know if anyone might be interested in updating it and getting it re-submitted to WordPress plugin directory?

**Andy Mabbett** - December 22, 2025
@Vincent Pai – I have no coding knowledge. The good news is that, quite by chance, I am able to announce that Roy Boverhof has just done a lot of work on the plug-in and issued v.1.0 – see the update, above!

---

## Contributors

- **Andy Mabbett** - ORCID: 0000-0001-5882-6823 (Concept, requirements, wireframe)
- **Roy Boverhof** - ORCID: 0000-0002-7299-680X (Developer, Elsevier)
- **Philip John** - Contributor (pull requests for structure improvements)
