---
# More detailed instructions (including how to fill these variables for an # online workshop) are available at https://carpentries.github.io/workshop-template/customization/index.html#yaml-header
# Required variables
venue: "University library Duisburg-Essen"        # brief name of the institution that hosts the workshop without address (e.g., "Euphoric State University")
address: "Lotharstr. 65, 47057 Duisburg & Universitätsstraße 9-11, 45141 Essen"      # full street address of workshop (e.g., "Room A, 123 Forth Street, Blimingen, Euphoria"), videoconferencing URL, or 'online'
country: "de"      # lowercase two-letter ISO country code such as "fr" (see https://en.wikipedia.org/wiki/ISO_3166-1#Current_codes) for the institution that hosts the workshop
language: "en"     # lowercase two-letter ISO language code such as "fr" (see https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) for the workshop
latitude: "51"     # decimal latitude of workshop venue - this should be a number greater than or equal to -90, and less than or equal to 90 (use https://www.latlong.net/)
longitude: "6"    # decimal longitude of the workshop venue - this should be a number greater than or equal to -180, and less than or equal to 180 (use https://www.latlong.net)
humandate: "May 13 – Sep 8, 2027 (selected Wednesdays & Thursdays, see schedule)"    # human-readable dates for the workshop (e.g., "Feb 17-18, 2020")
humantime: "Times vary by session, see schedule"    # human-readable times for the workshop e.g., "9:00 am - 4:30 pm CEST (7:00 am - 2:30 pm UTC)"
startdate: 2027-05-13      # machine-readable start date for the workshop in YYYY-MM-DD format like 2015-01-01
enddate: 2027-09-08        # machine-readable end date for the workshop in YYYY-MM-DD format like 2015-01-02
instructor: ["Sarah Ann Stock"] # boxed, comma-separated list of instructors' names as strings, like ["Kay McNulty", "Betty Jennings", "Betty Snyder"]
helper: ["tba"]     # boxed, comma-separated list of helpers' names, like ["Marlyn Wescoff", "Fran Bilas", "Ruth Lichterman"]
email: ["sarah.stock@uni-due.de"]    # boxed, comma-separated list of contact email addresses for the host, lead instructor, or whoever else is handling questions, like ["marlyn.wescoff@example.org", "fran.bilas@example.org", "ruth.lichterman@example.org"]
# Optional variables
collaborative_notes:  # URL for the workshop collaborative notes, e.g. an Etherpad or Google Docs document (e.g., https://pad.carpentries.org/2015-01-01-euphoria)
eventbrite:           # alphanumeric key for Eventbrite registration, e.g., "1234567890AB" (if Eventbrite is being used)
what3words:           # what3words (https://what3words.com) address of the workshop venue, without leading slashes e.g. "globe.lessening.computers"


### Workshop series content ###
# The individual workshops live in the _events/ folder (one file per event,
# incl. registration_url and the "Prepare" page).

locations:
  - name: "Campus Duisburg"
    address: "University Library, Lotharstr. 65, 47057 Duisburg"
  - name: "Campus Essen"
    address: "University Library, Universitätsstr. 9–11, 45141 Essen"

hero_title: "Two campuses."
hero_emphasis: "Practical computing skills for research."

workshop_introduction: >-
  Free, beginner-friendly, hands-on workshops for researchers, doctoral
  candidates and staff at the University of Duisburg-Essen who want to work
  more confidently with data, code and computational tools. Pick the
  sessions that fit your needs.

workshop_requirements:
  heading: "Come ready to learn"
  description: >-
    Bring a Mac, Windows or Linux laptop (on which you can install software)
    and its charging cable. Setup instructions for each session are on its
    Prepare page.
  default_laptop_support: >-
    Please complete the setup before the session. If something does not
    work, contact us in advance or arrive a few minutes early.
  default_capacity:           # e.g. 20 – leave empty to hide the sentence
  default_registration_notice: >-
    Registration is required for each session via the Register button.

# "Pathway" box below the workshop list (set enabled: false to hide it)
certificate:
  enabled: true
  invitation: "Recommended pathway"
  pathway_heading: "You don't have to attend everything."
  pathway_description: >-
    Every session can be booked on its own. For a solid foundation we
    recommend one Unix Shell session, one Git session, and one Python
    lesson – either "Programming with Python" or "Plotting and Programming
    in Python" (both parts). That's four meetings in total.
  requirements:
    - count: 1
      label: "Unix Shell"
    - count: 1
      label: "Git"
    - count: 1
      label: "Python lesson (Part I + II)"

# DON'T CHANGE THIS
layout: workshop
series_landing: true
---

{% include series-page.html %}
