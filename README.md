# Retrograde Planets Calendar: 2026-2027

This repository provides iCalendar feeds for planetary retrograde periods and daily Moon phases across 2026 and 2027.

## 2026 calendar

- [Subscribe to the 2026 calendar](webcal://raw.githubusercontent.com/peesheena/retrograde-planets-2026-2027/main/retrograde-planets-2026.ics)
- [Download the 2026 ICS file](https://raw.githubusercontent.com/peesheena/retrograde-planets-2026-2027/main/retrograde-planets-2026.ics)

The 2026 feed flags each retrograde start and end as a timed event using the exact Sydney station moments (`Australia/Sydney`). Calendar apps convert event times to the viewer's time zone. Descriptions retain the original Sydney time and station degree. It includes periods that began in 2025 or end in 2027.

## 2027 calendar

- [Subscribe to the 2027 calendar](webcal://raw.githubusercontent.com/peesheena/retrograde-planets-2026-2027/main/retrograde-planets-2027.ics)
- [Download the 2027 ICS file](https://raw.githubusercontent.com/peesheena/retrograde-planets-2026-2027/main/retrograde-planets-2027.ics)

The 2027 calendar flags the start and end dates supplied for each period active during 2027, including periods that began in 2026 or end in 2028. These are all-day date markers because exact station times were not supplied; unlike the 2026 timed feed, their dates do not shift by viewer time zone.

## Daily Moon phases

- [Subscribe to the daily Moon phase calendar](webcal://raw.githubusercontent.com/peesheena/retrograde-planets-2026-2027/main/moon-phases-2026-2027.ics)
- [Download the Moon phase ICS file](https://raw.githubusercontent.com/peesheena/retrograde-planets-2026-2027/main/moon-phases-2026-2027.ics)

The feed has one all-day entry for every date from 1 January 2026 through 31 December 2027. Each entry gives the Moon's phase and illuminated fraction at noon in Sydney, Australia. Dates stay fixed as all-day entries; the phase snapshot is based on Sydney local time.

## Events

| Planet | Retrograde begins (Sydney) | Retrograde ends (Sydney) |
| --- | --- | --- |
| Jupiter | 12 Nov 2025, 03:41 | 11 Mar 2026, 14:30 |
| Mercury | 26 Feb 2026, 17:48 | 21 Mar 2026, 06:33 |
| Pluto | 7 May 2026, 01:34 | 16 Oct 2026, 13:40 |
| Mercury | 30 Jun 2026, 03:36 | 24 Jul 2026, 08:58 |
| Neptune | 7 Jul 2026, 20:55 | 13 Dec 2026, 09:17 |
| Saturn | 27 Jul 2026, 05:56 | 11 Dec 2026, 10:31 |
| Chiron | 4 Aug 2026, 06:10 | 6 Jan 2027, 22:01 |
| Uranus | 11 Sep 2026, 04:27 | 8 Feb 2027, 23:29 |
| Venus | 3 Oct 2026, 17:16 | 14 Nov 2026, 11:27 |
| Mercury | 24 Oct 2026, 18:12 | 14 Nov 2026, 02:54 |
| Jupiter | 13 Dec 2026, 11:56 | 13 Apr 2027, 12:11 |

## Source

2026 retrograde dates, times, and station degrees are transcribed from the [Astro-Seek 2026 retrograde planets calendar](https://horoscopes.astro-seek.com/retrograde-planets-astrology-calendar-2026#list). 2027 retrograde dates, signs, and degrees were supplied separately; exact times were not available. Daily Moon phase and illumination values come from the [U.S. Naval Observatory Astronomical Applications API](https://aa.usno.navy.mil/data/api), queried for Sydney at local noon.
