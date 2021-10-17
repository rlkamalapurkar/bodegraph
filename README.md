# bodegraph
A few small modifications to Robert Papanicola's BodeGraph package.
- Fixed a bug where `\POAmpAsymp{a}{b}` generates a blank plot for b >= 2.
- Added support for asymptotic Bode plots of real poles and zeros in the right half plane.
- Added support for asymptotic Bode plots of complex conjugate pairs of poles and zeros with negative ζ.
- When loaded using the option `linear`:
  - `\POArgAsymp` changes slopes a decade before and after a pole/zero.
  - `\SOArgAsymp` changes slopes at ω<sub>n</sub>/10<sup>ζ</sup> and 10<sup>ζ</sup>ω<sub>n</sub>.

*Call `\BodeGraph` with the option `samples=300` (or more, as needed) to get accurate asymptotic phase plots.*
