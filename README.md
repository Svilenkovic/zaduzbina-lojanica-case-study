<a href="https://zaduzbinalojanica.rs/"><img src="media/cover.jpg" alt="Zadužbina Jovo Lojanica Stupljanin, home page on a laptop and a phone" width="100%"></a>

# Zadužbina Jovo Lojanica Stupljanin

Rebuilt site for a Sjenica endowment that researches foreign aid to Serbia in the Great War, moved off Drupal 7 along with its hosting and mail.

**[zaduzbinalojanica.rs](https://zaduzbinalojanica.rs/)** · [Srpski](README.sr.md)

> [!NOTE]
> Client project. The source code belongs to the client and stays in a private repository. This page describes what I built and how.

<table>
  <tr><td><b>Client</b></td><td>Jovo Lojanica Stupljanin Endowment</td></tr>
  <tr><td><b>Industry</b></td><td>Research into foreign humanitarian aid to Serbia in the Great War</td></tr>
  <tr><td><b>Location</b></td><td>Sjenica, Serbia</td></tr>
  <tr><td><b>Type</b></td><td>Bilingual multi-page website</td></tr>
  <tr><td><b>My role</b></td><td>Redesign, development, migration, hosting and maintenance</td></tr>
  <tr><td><b>Stack</b></td><td>PHP 8.3, SQLite, nginx</td></tr>
</table>

## About the project

The endowment researches foreign humanitarian aid to Serbia in the Great War: the countries, missions and people who treated, protected and helped. It collects documents, photos, letters and diaries, and organizes an international scientific conference in Sjenica. Its old site ran on Drupal 7. I replaced it and moved the hosting and mailboxes to my server without losing a single message.

The new site is in Serbian Cyrillic with an English version: about 36 pages that PHP 8.3 renders from SQLite. It has no forms at all; conference registrations and historical material arrive by email. The page for sending material lists what to include and says plainly what happens next: the original stays with its owner, the endowment keeps a digital copy, and every published item names where it came from.

## What I built

- The old Drupal 7 site rebuilt as server-rendered PHP 8.3 with SQLite
- About 36 pages in Serbian Cyrillic and English
- A conference section with the programme and a list of what a registration has to contain
- Pages on the six research areas, the countries that helped, people and historical records
- A page for sending historical material that explains what happens to originals and copies
- Hosting and mailboxes moved to my server with no mail lost

## Results

| | Performance | Accessibility | Best practices | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Mobile | 89 | 100 | 100 | 100 |
| Desktop | 100 | 100 | 100 | 100 |

Lighthouse, lab test of the live site, September 2026.

## Screenshots

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Zadužbina Jovo Lojanica Stupljanin, home page on a 1440 px screen"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Zadužbina Jovo Lojanica Stupljanin, home page on a phone"></td>
  </tr>
</table>

---

<sub>Built by [D. Svilenković](https://svilenkovic.com).</sub>
