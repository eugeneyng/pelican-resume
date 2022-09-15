### About
The initial theme was designed by Xiaoying Riley at 3rd Wave Media (http://themes.3rdwavemedia.com/). 

[Sharath Kumar](https://www.youtube.com/embed/T2nx6tj-ZH4) has made this into a Jekyll theme [online-cv](https://github.com/sharu725/online-cv). This is the port for Pelican.

I went ahead an improved it for my needs.

### Installation

To use this theme directly:
1. Clone this repo in any directory.
```
git clone https://github.com/eugeneyng/pelican-resume.git
```
2. Edit your Pelican settings file (`pelicanconf.py`) to include this line:
```
THEME = "/path-to-directory/resume"
```

### Configuration

Add the following variables in your Pelican setting file.

Change these to add you own information to generate a personalised web resume.
```
# Theme
THEME = "./pelican-resume"

# Profile information
NAME = "Your Name Here"
TAGLINE = "Job Title"
PIC = "profile.png" # Make sure you put a profile.png in your ./content folder

# Sidebar links
EMAIL = "email@email.com"
PHONE = "123 456 7890"
WEBSITE = "my.website"
PORTFOLIO = "my.portfolio.website"
LINKEDIN = "mylinkedin"
GITHUB = "mygithub"
PDF = "mypdfresume"

CAREER_SUMMARY = "I'm a web developer"

EDUCATION = [
	{
		"degree": "B.S., Computer Science",
		"institution": "University of Pelican",
		"time": "2022-2023"
	}
]

EXPERIENCES = [
	{
		"job_title": "Developer",
		"time": "Past - Present",
		"company": "Self-Employed",
		"details": [
      {
        "description": "I do a lot of web developing",
        "inner_details": [
          "I did this",
          "and I did this",
          "and then I did this",
          "and then I did that",
        ]
      },
      {"description": "I also do a lot of dev webbing"},
    ],
	},
]

INTERESTS = [
  {
    "item": "Pelican",
    "link": ""
  },
]

LANGUAGES = [
	{
		"name": "English",
		"description": "Native"
	}
]

PROJECT_INTRO = ""

PROJECTS = [
	{
		"title": "Pelican Theme",
    "details": [
      {
        "description": "Modified a Pelican theme"
      },
      {
        "description": "even though I know nothing"
      }
    ],
    "link": ""
	},
]

SKILLS = [
	{
    "title": "ANSYS",
    "level": "75"
  },
  {
    "title": "HTML/CSS",
    "level": "95"
  }
]
```

Check out for more themes: [**Pelican Themes**](http://www.pelicanthemes.com)