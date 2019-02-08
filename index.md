# scale.qihardware.org

Journal for Hardware, Software, Crypto and China.

## Current: {{ site.data.2019.week.05.title }}

_Go to the data file, re-order based upon quality, commit
if our proof-of-work right now until can implement
some coin moderation up and down <a href="https://github.com/QiHardware/scale.qihardware.org/blob/master/_data/2019/week/05.yml">Week 05 Links</a> (requires github account)_


<ul>
{% for link in site.data.2019.week.05.links %}
  <li>
    <a href="{{ link.url }}">
      {{ link.url }}
    </a><br /><em>posted by {{ link.postedBy }}{% if link.likedBy %}, liked by {{ link.likedBy }}{% endif %}</em>
  </li>
{% endfor %}
</ul>

## Guideliness

- Weekly roundup of articles, research, comments on the intersection of crypto, hardware, software, and culture
- Open for anyone to add links, reorder, or edit
- Each Friday, at the end of the business day PST, the top links are compiled into a PDF for release for weekend offline reading

## Future

- Add up/down voting powered by ETH to rank quality of submissions
- Looking for sponsorship (in ETH) to underwrite a more formal journal

## Old Issues

- Pre-2019 archives: https://github.com/rejon/scale-2004


## Contact

- <a href="mailto:ai@qihardware.org">ai@qihardware.org</a>
- Twitter: <a href="https://twitter.com/qihardware">https://twitter.com/qihardware</a>
- Telegram: <a href="https://t.me/qihardware">https://t.me/qihardware</a>


## Contribute

- Add your links to the top of the weekly roundup.
- https://github.com/QiHardware/scale.qihardware.org (code + site)
