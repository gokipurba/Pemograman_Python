# Kelas Pemograman Pyhton
=========
Kumpulan Latihan dan Tugas Presensi KULIAH PYTHON

Change Log
==========

2018-09-30: v2.13.4
--------------------

* Fixed [bug #524] and [bug #526]: Due to v2.13.3 fix, Markdown Here didn't work in Thunderbird with a non-English UI.
  - Thanks to [KSR-Yasuda](https://github.com/KSR-Yasuda), [ensleep](https://github.com/ensleep), [Pedro Silva](https://github.com/pmanu93), [Christophe Meyer](https://github.com/stombi), [littdky](https://github.com/littdky), [Michael Lashkevich](https://github.com/lashkevi), [morsedl](https://github.com/morsedl).


2018-09-11: v2.13.3
--------------------

* [Fixed bug #495](https://github.com/adam-p/markdown-here/issues/495): Markdown Here stopped working in Thunderbird version 60 (due to changes in Thunderbird).
  - Thanks to [dugite-code](https://github.com/dugite-code) for the [PR](https://github.com/adam-p/markdown-here/pull/518) to fix it. Also thanks to: [Marc-Alexandre Espiaut](https://github.com/marespiaut), [Tehmul Ghyara](https://github.com/tehmul), [Pedro Silva](https://github.com/pmanu93), [PackElend](https://github.com/PackElend), [qolii](https://github.com/qolii), [Francisco Pina-Martins](https://github.com/StuntsPT), [evazquez00](https://github.com/evazquez00).

* [Fixed bug #435](https://github.com/adam-p/markdown-here/issues/435): On some pages, Markdown Here would spew cross-origin exceptions to the console. This was due to MDH trying to determine if a focused iframe-within-an-iframe was renderable.
  - Thanks to [lincoln-b](https://github.com/lincoln-b) for reporting it.

* [Fixed bug #427](https://github.com/adam-p/markdown-here/issues/427): In Chrome and Firefox (at least for some pages), after rendering the resulting text was selected.
  - Thanks to [nedchu](https://github.com/nedchu) for reporting it.
