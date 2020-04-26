---
title: "About the author"
date: 2020-04-26T12:00:00+01:00
layout: "about"
---
{{< highlight python >}}
import author

author.about = {
  'name': 'David Schenk',
  'born': 1992,
  'country': 'Germany',
  'mail': 'blog@pydave.de',
  'languages': ['German', 'English', 'Spanish'],
  'job':  {
    'title': 'Consultant',
    'company': 'CONET Solutions GmbH',
    'department': 'Data Intelligence'
  },
  'slogan': 'start small. stay tuned.',
  'hobbys': ['Snowboarding', 'Motorcycling'],
  'favorite': {
    'programming language': {
      'most loved': 'python',   # obviously
      'most wanted': 'go'
    },
    'database': 'MongoDB',
    'ide': 'PyCharm',   # i love jetbrains, it doesn't even matter what you say
    'platform': 'Linux'
  },
  'social': {
    'xing': 'https://www.xing.com/profile/David_Schenk4',
    'linkdin': 'https://www.linkedin.com/in/david-schenk'
  }
}
{{< / highlight >}}
