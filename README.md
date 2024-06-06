# Introduction

qlcplus fixture files for:

- Gruolin GL-A001 laser
- Olaalite OL-A001 laser, which appears to be near identical to Gruolin GL-A001
- Olaalite OL-A002 laser, which is idential or near-identical to Gruolin GL-A02
  - it may not even be possible to purchase Gruolin GL-A02 as such, as Olaalite OL-A002 arrives

Currently, only 34-channel (advanced/customizable) modes are available here.

5/6-channel, simplified modes should also be added.

🚧 *WORK IN PROGRESS* 🚧

## Lasers Info

### Gruolin GL-A001

The laser basically allows two (almost) independent images to be projected.

- 6CH Simple Line & Annimation Pattern at DMX address `E.001` (not implemented here yet)
- 34CH Proffessional Line & Animation Pattern at DMX address `A.001`

#### Amazon Product Page

https://www.amazon.com/Gruolin-Animation-Activated-Perefct-Lighting/dp/B09ZY8Z96T/

#### User Manual PDF

- from Amazon: https://m.media-amazon.com/images/I/B1WQMfSwivL.pdf
- copy: TODO

#### Review

https://happytechfam.online/gruolin-3d-animation-dj-party-laser-light-full-color-review/

#### Youtube

https://www.youtube.com/watch?v=fdpWfh7IOrY

### Olaalite OL-A001

Either same people/company (suddenly?) selling under a different name or some kind of clone of Gruolin GL-A001.

There could some, and maybe even important differences within parameters, but overall this appears to be a clone of GL-A001

The DMX addresses and channels are a little different:

- 5CH Simple Line & Annimation Pattern at DMX address `J.001` (not implemented here yet)
- 34CH Proffessional Line & Animation Pattern at DMX address `D.001`

 I expect everything or almost everything to work with the fixture mapping for Gruolin GL-A001. If somebody wants to test drive this laser with my mapping for GL-A001 or dive into the user manual to pick out all differences in DMX values by all means! I am unable to do so at the moment.

#### Amazon Product Page

https://www.amazon.com/gp/product/B0B36G4TRN

#### User Manual PDF

- from Amazon: https://m.media-amazon.com/images/I/91kl4jcOB1L.pdf
- copy: TODO

### Gruolin GL-A02 / Olaalite OL-A002

I purchased this as a Gruolin product, which shows GL-A02 in product images on Amazon. However, the laser that arrived is clearly labeled as Olaalite OL-A002. Thus, you may not be able to purchase Gruolin GL-A02 as such.

This upgrade appears to:
- allow independent gallery and line/beam mode for the second pattern
- rated 30w instead of 20w
- likely rearranges how some parameters and effects work

DMX addresses:

- 6CH Simple Line & Annimation Pattern at DMX address `E.001` (not implemented here yet)
- 34CH Proffessional Line & Animation Pattern at DMX address `D.001`


#### Amazon Product Page

https://www.amazon.com/gp/product/B0CCMM8BHJ/

Amazon product page presents the laser as Gruolin GL-A02, but the purchased laser arrives branded as Olaalite OL-A002

#### User Manual

- copy: todo

## Installation

**Gruolin GL-A001**? => use `gla001_34ch.qxf`

**Olaalite OL-A001**? => use `gla001_34ch.qxf`, but be aware there may be minor discrepancies within some parameters

**Gruolin GL-A02** or **Olaalite OL-A002**? => use `ola002_34ch.qxf`

### Linux (Tested on Fedora 40)

Copy `gla001_34ch.qxf` and/or `ola002_34ch.qxf` (or add soft-link(s) to be accessible at):

User library: **`~/.qlcplus/fixtures`**

(Re)start

### Windows

Copy `gla001_34ch.qxf` and/or `ola002_34ch.qxf` to:

`C:\Users\[user name]\QLC+\fixtures`

(Re)start

### OSX

Copy `gla001_34ch.qxf` and/or `ola002_34ch.qxf` to:

`~/Library/Application Support/QLC+/fixtures`

(Re)start

## Screenshots

|   |   |
| - | - |
| ![github_screenshot_2](https://github.com/HoneyHazard/qlcplus_gruolin_gl-a001/assets/8847050/4f0aaa16-32f7-403e-adbe-213d205f4b83) | ![github_screenshot_1](https://github.com/HoneyHazard/qlcplus_gruolin_gl-a001/assets/8847050/f064c725-77aa-4f4e-862f-7c0550022cae) <br /> ![github_screenshot_0](https://github.com/HoneyHazard/qlcplus_gruolin_gl-a001/assets/8847050/ead0f690-793c-49d7-90c1-49dae3029874) |


# TODO and Further Plans

Read [TODO.md](https://github.com/HoneyHazard/qlcplus_gruolin_olaalite_a001_a002/blob/main/TODO.md)
